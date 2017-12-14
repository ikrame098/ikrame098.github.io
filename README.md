<!doctype html>
<html>
  <head> 
  <style> 
    body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #333;
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
    url("https://static.pexels.com/photos/248515/pexels-photo-248515.png");
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
    <h1>Welcome to Acme Web Solutions</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci eum error earum soluta voluptatum nisi laboriosam eos saepe asperiores dolorum.</p>
    <a href="#section-b" class="btn">Read More</a>
  </div>
</header>

<!-- Main Area -->
<main id="main">
  <!-- Section A -->
  <section id="section-a" class="grid">
    <div class="content-wrap">
      <h2 class="content-title">Web & Application Development</h2>
      <div class="content-text">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe sint eligendi possimus? Unde officiis magnam laborum ipsa distinctio odio, vero dolores dicta aliquam aperiam repellendus. Perferendis officiis deserunt velit voluptas nobis sequi
          animi totam, accusantium, ex eius quia, natus quo?</p>
      </div>
    </div>
  </section>

  <!-- Section B -->
  <section id="section-b" class="grid">
    <ul>
      <li>
        <div class="card">
          <img src="https://static.pexels.com/photos/574077/pexels-photo-574077.jpeg" alt="">
          <div class="card-content">
            <h3 class="card-title">Web Development</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum culpa neque quo eum et quasi velit voluptatum cum maiores exercitationem.</p>
          </div>
        </div>
      </li>
      <li>
        <div class="card">
          <img 
src="https://static.pexels.com/photos/261628/pexels-photo-261628.jpeg" alt="">
          <div class="card-content">
            <h3 class="card-title">Mobile Applications</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum culpa neque quo eum et quasi velit voluptatum cum maiores exercitationem.</p>
          </div>
        </div>
      </li>
      <li>
        <div class="card">
          <img src="https://static.pexels.com/photos/265087/pexels-photo-265087.jpeg" alt="">
          <div class="card-content">
            <h3 class="card-title">Tech Marketing</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum culpa neque quo eum et quasi velit voluptatum cum maiores exercitationem.</p>
          </div>
        </div>
      </li>
    </ul>
  </section>

  <!-- Section C -->
  <section id="section-c" class="grid">
    <div class="content-wrap">
      <h2 class="content-title">We handle all of your digital needs</h2>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime nam rerum vel earum error fugiat cupiditate, dolore eius! Minus, explicabo.</p>
    </div>
  </section>

  <!-- Section D -->
  <section id="section-d" class="grid">
    <div class="box">
      <h2 class="content-title">Contact Us</h2>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eum, suscipit. Rerum ducimus a quod, ut et voluptas obcaecati unde fuga.</p>
      <p>contact@acmewebsolutions.test</p>
    </div>
    <div class="box">
      <h2 class="content-title">About Our Company</h2>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio earum porro deserunt, deleniti, quae facere repudiandae, officiis est exercitationem nobis iusto doloremque! Soluta excepturi in aut suscipit amet temporibus quo?</p>
    </div>
  </section>
</main>

<!-- Footer -->
<footer id="main-footer" class="grid">
  <div>Acme Web Solutions</div>
  <div>Project By <a href="http://traversymedia.com" target="_blank">Traversy Media</a></div>
</footer>

</body>


