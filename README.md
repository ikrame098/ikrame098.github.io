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
body{
  font: 15px/1.5 Arial, Helvetica,sans-serif;
  padding:0;
  margin:0;
  background-color:#f4f4f4;
}

/* Global */
.container{
  width:80%;
  margin:auto;
  overflow:hidden;
}

ul{
  margin:0;
  padding:0;
}

.button_1{
  height:38px;
  background:#e8491d;
  border:0;
  padding-left: 20px;
  padding-right:20px;
  color:#ffffff;
}

.dark{
  padding:15px;
  background:#35424a;
  color:#ffffff;
  margin-top:10px;
  margin-bottom:10px;
}

/* Header **/
header{
  background:#35424a;
  color:#ffffff;
  padding-top:30px;
  min-height:70px;
  border-bottom:#e8491d 3px solid;
}

header a{
  color:#ffffff;
  text-decoration:none;
  text-transform: uppercase;
  font-size:16px;
}

header li{
  float:left;
  display:inline;
  padding: 0 20px 0 20px;
}

header #branding{
  float:left;
}

header #branding h1{
  margin:0;
}

header nav{
  float:right;
  margin-top:10px;
}

header .highlight, header .current a{
  color:#e8491d;
  font-weight:bold;
}

header a:hover{
  color:#cccccc;
  font-weight:bold;
}

/* Showcase */
#showcase{
  min-height:400px;
  background:url('../img/showcase.jpg') no-repeat 0 -400px;
  text-align:center;
  color:#ffffff;
}

#showcase h1{
  margin-top:100px;
  font-size:55px;
  margin-bottom:10px;
}

#showcase p{
  font-size:20px;
}

/* Newsletter */
#newsletter{
  padding:15px;
  color:#ffffff;
  background:#35424a
}

#newsletter h1{
  float:left;
}

#newsletter form {
  float:right;
  margin-top:15px;
}

#newsletter input[type="email"]{
  padding:4px;
  height:25px;
  width:250px;
}

/* Boxes */
#boxes{
  margin-top:20px;
}

#boxes .box{
  float:left;
  text-align: center;
  width:30%;
  padding:10px;
}

#boxes .box img{
  width:90px;
}

/* Sidebar */
aside#sidebar{
  float:right;
  width:30%;
  margin-top:10px;
}

aside#sidebar .quote input, aside#sidebar .quote textarea{
  width:90%;
  padding:5px;
}

/* Main-col */
article#main-col{
  float:left;
  width:65%;
}

/* Services */
ul#services li{
  list-style: none;
  padding:20px;
  border: #cccccc solid 1px;
  margin-bottom:5px;
  background:#e6e6e6;
}

footer{
  padding:20px;
  margin-top:20px;
  color:#ffffff;
  background-color:#e8491d;
  text-align: center;
}

/* Media Queries */
@media(max-width: 768px){
  header #branding,
  header nav,
  header nav li,
  #newsletter h1,
  #newsletter form,
  #boxes .box,
  article#main-col,
  aside#sidebar{
    float:none;
    text-align:center;
    width:100%;
  }

  header{
    padding-bottom:20px;
  }

  #showcase h1{
    margin-top:40px;
  }

  #newsletter button, .quote button{
    display:block;
    width:100%;
  }

  #newsletter form input[type="email"], .quote input, .quote textarea{
    width:100%;
    margin-bottom:5px;
  }
}

