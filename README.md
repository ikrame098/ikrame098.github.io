
<html>
  <head> 
  <style> 
    body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: 	#B0E0E6;
  color: #fff;
  font-size: 1.1em;
  line-height: 1.5;
  text-align: center;
}

img {
  display: block;
  width: 100%;
  height: auto;
}

h1,
h2,
h3 {
  margin: 0;
  padding: 1em 0;
}

p {
  margin: 0;
  padding: 1em 0;
}

.btn {
  display: inline-block;
  background: #333;
  color: #fff;
  text-decoration: none;
  padding: 1em 2em;
  border: 1px solid #666;
  margin: 0.5em 0;
}

.btn:hover {
  background: #eaeaea;
  color: #333;
}

/* Header Showcase */

#showcase {
  min-height: 450px;
  color: #fff;
  text-align: center;
}

#showcase .bg-image {
  position: absolute;
  background: #333
    url("data:image/jpeg;base64,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");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 450px;
  z-index: -1;
  opacity: 0.4;
}

#showcase h1 {
  padding-top: 100px;
  padding-bottom: 0;
}

#showcase .content-wrap,
#section-a .content-wrap {
  padding: 0 1.5em;
}

/* Section A */

#section-a {
  background: #eaeaea;
  color: #333;
  padding-bottom: 2em;
}

/* Section B */

#section-b {
  padding: 2em 1em 1em;
}

#section-b ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

#section-b li {
  margin-bottom: 1em;
  background: #fff;
  color: #333;
}

.card-content {
  padding: 1.5em;
}

/* Section C */

#section-c {
  background: #fff;
  color: #333;
  padding: 2em;
}

/* Section D / Boxes */

#section-d .box {
  padding: 2em;
  color: #fff;
}

#section-d .box:first-child {
  background: #2690d4;
}

/* Footer */

#main-footer {
  padding: 2em;
  background: #000;
  color: #fff;
  text-align: center;
}

#main-footer a {
  color: #2690d4;
  text-decoration: none;
}

/* Media Queries */

@media (min-width: 700px) {
  .grid {
    display: grid;
    grid-template-columns: 1fr repeat(2, minmax(auto, 25em)) 1fr;
  }

  #section-a .content-text {
    columns: 2;
    column-gap: 2em;
  }

  #section-a .content-text p {
    padding-top: 0;
  }

  .content-wrap,
  #section-b ul {
    grid-column: 2/4;
  }

  .box,
  #main-footer div {
    grid-column: span 2;
  }

  #section-b ul {
    display: flex;
    justify-content: space-around;
  }

  #section-b li {
    width: 31%;
  }
}

    
    
  </style> 
</head> 

<body>



<header id="showcase" class="grid">
  <div class="bg-image"></div>
  <div class="content-wrap">
    <h1>Welkome</h1>
    <p>Ikrame El Kandoussi</p>
    <a href="#section-b" class="btn">Read More</a>
  </div>
</header>

<!-- Main Area -->
<main id="main">
  <!-- Section A -->
  <section id="section-a" class="grid">
    <div class="content-wrap">
      <h2 class="content-title">De mens die in harmonie leeft met de natuur, is helder als water.
</h2>
      <div class="content-text">
        <p>

In dit werkstuk hebben wij een onderzoek beschreven dat wij de afgelopen weken hebben gedaan. Een paar weken geleden zaten wij in de les te luisteren naar wat onze aardrijkskundelerares te vertellen had. De docente vertelde dat wij een werkstuk moesten maken over water. Wij kozen voor het onderwerp: Doorspoelen met regenwater. Waarom wij voor dit onderwerp hebben gekozen, is heel simpel, onze school gebruikt al jaren regenwater en we wilden graag weten hoe dit nou precies zat. Onze hoofdvraag was eigenlijk: Kunnen wij en de toekomst heel de regio Den Bosch voorzien van regenwater voor het doorspoelen van toiletten? En  wat zijn de effecten hiervan? Dit lichten wij  toe aan de hand van een paar deelvragen: ’’Waarom zou je gebruik maken van regenwater voor het doorspoelen van de toilet?’’ In deze deelvraag leggen we uit wat de voordelen en de nadelen zijn van duurzaam naar de wc gaan. 
De volgende deelvraag is:’’Wat voor effect heeft het gebruik van regenwater voor doorspoelen op de omgeving?’’ bij deze deelvraag bekijken wij de effecten op het gebied van planten, dieren en de vertragingstijd. 
Als derde deelvraag hebben wij ‘’Wat is ervoor nodig om de regio Den Bosch te voorzien van genoeg regenwater voor het doorspoelen van de toiletten?’’ Hier leggen we stap voor stap hoe wij dit plan kunnen realiseren. 
Als vierde deelvraag hebben wij ‘’Is het economisch aantrekkelijk om regenwater te gebruiken in plaats van het gewoon drinkwater?’’ Hier bekijken wij of er economische voordelen zijn aan het plan. 
En tot slot hebben we nog een deelvraag:”zijn er nog meer mogelijkheden voor het gebruik van regenwater in plaats van drinkwater?’’ Hier bespreken wij de verdere mogelijkheden van regenwater. Verder zullen wij een aantal bronnen gebruiken om beter uitleg te kunnen geven. De hoofdstukken zullen beginnen met een korte inleiding en vanuit de inleiding komen er alinea’s die de deelvragen gaan beantwoorden. Wij hebben het ook een paar keer over Gerard, dit is een man die bij ons op school mee heeft gewerkt aan het regenwatersysteem.


<br>Veel plezier met lezen!</br>
</p>
      </div>
    </div>
  </section>

  <!-- Section B -->
  <section id="section-b" class="grid">
    <ul>
      <li>
        <div class="card">
          <img src="http://www.exellent.be/images/infopages/vraagteken.jpg" alt="">
          <div class="card-content">
            <h3 class="card-title">Waarom</h3>
            <p>Duurzaam water zou een must moeten zijn voor elk persoon. Drinkwater is schaars en kostbaar. Meer dan een miljard mensen hebben geen beschikking over schoon drinkwater en dit zal de komende jaren alleen maar toenemen.</p>
          </div>
        </div>
      </li>
      <li>
        <div class="card">
          <img src="https://pbs.twimg.com/profile_images/646682042374209536/ryGFm6H1.jpg" alt="">
          <div class="card-content">
            <h3 class="card-title">Groene school</h3>
            <p>Wij zijn naar een medewerker van school gegaan genaamd Gerard. Gerard heeft ons uitgelegd hoe het watersysteem van school precies werkte, welke problemen het watersysteem mee brengen en heeft ons uitgelegd gegeven over hoe de school duurzaam probeert te zijn. In deze deelvraag vertellen wij je wat Gerard ons heeft verteld. </p>
          </div>
        </div>
      </li>
      <li>
        <div class="card">
          <img 
src="http://www.opvakantiehuis.nl/sites/default/files/tips-plaatje_0.png" alt="">
          <div class="card-content">
            <h3 class="card-title">Tips</h3>
            <p>Wij hebben in dit werkstuk voornamelijk over gehad dat doorspoelen met regenwater erg goed is voor het milieu. In dit hoofdstuk vertellen wij je over de verdere mogelijkheden die je kun doen met regenwater. .</p>
          </div>
        </div>
      </li>
      <li>
        <div class="card">
          <img src="http://media.nu.nl/m/m1nx95jansk3_sqr512.jpg/duitse-regering-ziet-opleving-economie.jpg" alt="">
          <div class="card-content">
            <h3 class="card-title">Economie</h3>
            <p>Het is gratis, zowel geliefd als gehaat en valt in heel wat grotere hoeveelheden uit de hemel dan manna: regenwater. Is regenwater wel goed voor je portemonnee? </p>
          </div>
        </div>
      </li>
    </ul>
  </section>

  <!-- Section C -->
  <section id="section-c" class="grid">
    <div class="content-wrap">
      <h2 class="content-title">Over mij</h2>
      <p> Mijn naam is Ikrame El Kandoussi ik ben zeventien jaar oud en ben momenteel een leerling van klas 6 vwo van het Ds. Pierson College. Ik heb deze website gemaakt omdat ik een opdracht kreeg van mijn docent informatica. Ik hoop dat ik je meer informatie heb gegeven over het onderwerp water. Als je verdere vragen hebt kun je mij een bericht sturen en dan zal ik zo spoedig mogerijk reageren 
     groetje Ikrame </p>
    </div>
  </section>

  <!-- Section D -->
  <section id="section-d" class="grid">
    <div class="box">
      <h2 class="content-title">Vragen?</h2>
      <p>Voor vragen kun je mij bereiken op: </p>
      <p>5258@pierson.nl</p>
    </div>
    <div class="box">
      <h2 class="content-title">Quiz</h2>
     <p class="question">1. Hoeveel water verbruikt een persoon per jaar?</p>
<ul class="answers">
<input type="radio" name="q1" value="a" id="q1a"><label for="q1a">60.000 liter</label><br/>
<input type="radio" name="q1" value="b" id="q1b"><label for="q1b"> 52.000 liter </label><br/>
<input type="radio" name="q1" value="c" id="q1c"><label for="q1c">55.000</label><br/>
<input type="radio" name="q1" value="d" id="q1d"><label for="q1d">80.000 liter </label><br/>
</ul>




