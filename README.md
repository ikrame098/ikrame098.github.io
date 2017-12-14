<!DOCTYPE html>

<html lang="nl">

<head>
<title>De titel van je webpagina</title>
<meta charset="utf-8">
<meta name="description" content="beschrijving van je webpagina">
<meta name="viewport" content="initial-scale=1.0, width=device-width">
<link rel="stylesheet" href="basis.css" type="text/css" media="screen">
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js"></script>
</head>

<body>

<header><h1>Mijn eigen website</h1></header>

<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="wiezijnwij.html">Wie zijn wij</a></li>
<li><a href="hobbys.html">Hobby’s</a></li>
<li><a href="fotos.html">Foto’s</a></li>
<li><a href="links.html">Links</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</nav>

<article>

<h1>Morbi aliquam mi quis volutpat</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur bibendum orci sit amet odio varius pulvinar. Quisque malesuada iaculis nibh, a vulputate orci rutrum sed. In vitae neque nibh. Maecenas semper dolor nec orci vestibulum cursus. Phasellus vel eros urna, at laoreet lorem.</p>

<ul>
<li>Nam diam libero, vulputate non aliquet et, tempus consectetur magna.</li>
<li>Cum sociis natoque penatibus et magnis dis parturient montes.</li>
<li>Morbi consequat ornare arcu at convallis.</li>
</ul>

<p>Nulla et lacus elit, id dapibus ante. Ut vulputate aliquam consequat. In nulla quam, consectetur in consequat quis, facilisis non nisi.</p>

<img alt="roos" src="http://www.mijn-eigen-website.nl/images/roos.gif" style="float: right;">
<h2>Duis consectus</h2>
<p>Duis consectus vestibulum condimentum. Morbi bibendum, nisl id hendrerit rutrum, orci metus semper nulla, a condimentum augue turpis quis elit. Donec dolor velit, egestas sit amet faucibus non, placerat eget erat.</p>

<ol>
<li>Etiam lectus neque, hendrerit in feugiat ac, malesuada eu arcu.</li>
<li>Ut ipsum dui, sollicitudin eget viverra a, hendrerit in sapien.</li>
<li>Proin hendrerit orci eget nulla tristique sit amet volutpat arcu.</li>
</ol>

<p>Ut auctor viverra turpis id tincidunt. Curabitur eu lectus non orci interdum sagittis at condimentum justo. Donec porttitor massa tortor, et malesuada odio. Sed eget nisl sit amet mauris tempor ultrices ut eget erat. Mauris sit amet erat quis risus vehicula fermentum. Nulla sollicitudin pulvinar venenatis.</p>

</article> 

<footer>
<p>© 2017 Jouw eigen website</p>
</footer>

</body>

</html>
body { 
    font-family: "Trebuchet MS", sans-serif;
    font-size: 1em;
    padding: 0;
    margin: 0;
} 

header { 
    background-color: navy;
    box-sizing: border-box;
    padding: 2em 1em;
} 

header h1 {
    color: white;
    font-family: Georgia, serif;
    font-size: 2.5em;
    font-variant: small-caps;
    text-align: center;
}

nav { 
    background-color: maroon;
    box-sizing: border-box;
    font-size: .9em;
} 

nav ul { 
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav li { 
    border-top: 1px solid white;
    padding: .5em;
}

nav li:hover {
    background-color: navy;
}

nav li a {
    text-decoration: none;
    color: white;
}

article { 
    box-sizing: border-box;
    padding: 2em;
    min-height: 70vh;
}

article img {
    max-width: 100%;
}

article ul, #hoofdvak ol {
    list-style-position: outside;
    margin-left: 2em;
}

article h1 {
    color: maroon;
}

article h2 {
    color: navy;
}

footer { 
    background-color: navy;
    box-sizing: border-box;
    clear: both;
    color: white;
    font-size: .8em;
    padding: 2em;
    text-align: center;
}

@media screen and (min-width: 600px) {
    nav ul, article {
        max-width: 1000px;
        margin: 0 auto;
    }
    nav {
        font-size: 1em;
    }
    nav ul {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
     }
    nav ul li {
        border-top: none;
        -webkit-box-flex: 1;
        -ms-flex-positive: 1;
        flex-grow: 1;
    }
    nav li {
        text-align: center;
    }
}

