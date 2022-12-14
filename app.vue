<template>
  
  <nav>
    <div class="container">
      <img src="./images/logo.svg"/>
      <ul class="nav-ul">
        <a href="#">
          <li>About</li>
        </a>
        <a href="#">
          <li>Services</li>
        </a>
        <a href="#">
          <li>Projects</li>
        </a>
        <button class="btn">CONTACT</button>
      </ul>
    </div>
    <h1 class="nav-title">WE ARE CREATIVES</h1>
  </nav>

  <section class="first-section">
    <div class="first-section-container">
    <div class="first-section-first-div">
      <h3 class="first-section-title">Transform your brand</h3>
      <p class="first-section-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
        molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
        numquam blanditiis harum</p>
      <a class="first-section-tag" href="#">LEARN MORE</a>
    </div>

    <img class="transform-img" src="./images/desktop/image-transform.jpg" alt="">

    <img class="stand-out-img" src="./images/desktop/image-stand-out.jpg" alt="">

    <div class="first-section-second-div">
      <h3 class="first-section-title">Stand out to the right audience</h3>
      <p class="first-section-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
        molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
        numquam blanditiis harum</p>
      <a class="first-section-tag" href="#">LEARN MORE</a>
    </div>

    <div class="first-section-third-div">
      <h3 class="first-section-title">Graphic Design</h3>
      <p class="first-section-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
        molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
        numquam blanditiis harum</p>
    </div>

    <div class="first-section-fourth-div">
      <h3 class="first-section-title">Photography</h3>
      <p class="first-section-para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
        molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
        numquam blanditiis harum</p>
    </div>
    </div>
  </section>

  <section class="second-section">
      <h1>CLIENT TESTIMONIALS</h1>
    <div class="second-section-container">

      <div class="second-section-inner-div">
        <img src="./images/image-emily.jpg" alt="#">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
          molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
          numquam blanditiis harum</p>
        <p class="client-name">Emily R.</p>
        <p class="client-title">Marketing Director</p>
      </div>

      <div class="second-section-inner-div">
        <img src="./images/image-thomas.jpg" alt="#">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
          molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
          numquam blanditiis harum</p>
        <p class="client-name">Thomas S.</p>
        <p class="client-title">Chief Operating Officer</p>
      </div>

      <div class="second-section-inner-div">
        <img src="./images/image-jennie.jpg" alt="#">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
          molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum
          numquam blanditiis harum</p>
        <p class="client-name">Jennie F.</p>
        <p class="client-title">Business Owner</p>
      </div>
    </div>
  
  </section>

  <section class="third-section">
  <div class="third-section-container">
    <img src="./images/desktop/image-gallery-milkbottles.jpg" alt="#">
    <img src="./images/desktop/image-gallery-orange.jpg" alt="#">
    <img src="./images/desktop/image-gallery-sugarcubes.jpg" alt="#">
    <img src="./images/desktop/image-gallery-cone.jpg" alt="#">
  </div>
  </section>

  <footer>
    <div class="footer-container">
      <h1>sunnyside</h1>
      <div class="footer-first-div">
        <ul>
          <a href="#"><li>About</li></a>
          <a href="#"><li>Services</li></a>
          <a href="#"><li>Projects</li></a>
        </ul>
      </div>
      <div class="footer-second-div">
        <a href="#"><img src="./images/icon-facebook.svg" alt="#"></a>
        <a href="#"><img src="./images/icon-instagram.svg" alt="#"></a>
        <a href="#"><img src="./images/icon-twitter.svg" alt="#"></a>
        <a href="#"><img src="./images/icon-pinterest.svg" alt="#"></a>
      </div>
      <p class="my-name">Coded by Ahmet Cem Aydın</p>
    </div>
  </footer>
</template>

<style>
  *{
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body{
    padding: 0;
    margin: 0;
    background-color: hsl(167, 40%, 24%);
    overflow-x: hidden;
}

img{
    max-width: 100%;
}


/* navbar styling starts from here*/

a:hover, button:hover{
    opacity: 0.5;
}

nav{
    background-image: url("images/desktop/image-header.jpg");
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
    height: 650px;
    max-width: 1440px;
    margin: auto;
}

.container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;
    padding: 0 2em;
}

.nav-ul{
    display: flex;
    align-items: center;
    width: 400px;
    justify-content: space-between;
    list-style: none;
}

.nav-ul li{
    font-family: 'Barlow', sans-serif;
    font-weight: 500;
    color: hsl(0, 0%, 100%);
    
}

.nav-ul a{
    text-decoration: none;
}

.nav-ul button{
    font-family: 'Fraunces', serif;
    font-weight: 700;
    color:hsl(212, 27%, 19%);
    padding: 10px 20px;
    border-radius: 20px;
    border-style: none;
    height: 40px;
    width: auto;
    cursor: pointer;
}

.nav-title{
    text-align: center;
    color: hsl(0, 0%, 100%);
    font-size: 45px;
    letter-spacing: 8px;
    font-family: 'Fraunces', serif;
    text-decoration-line:underline;
    text-decoration-style: wavy;
    text-decoration-thickness: 3px;
}

/*.header-image{
    width: 100%;
    height: 650px;
    object-fit: cover;
    margin: auto;
    display: block;
    position: absolute;
    top: 0;
}*/


/* navbar styling ends*/


/* first-section styling starts from here */

.first-section{
    background-color: hsl(198, 62%, 26%);
}

.first-section-container{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(3, 1fr);
    max-width: 1440px;
    margin: 0 auto;
    align-items: center;
}

.first-section-first-div{
    padding-top:10em ;
    height: 600px;
    background-color: hsl(0, 0%, 100%);
}

.first-section-title{
    font-family: 'Fraunces', serif;
    font-size: 35px;
    font-weight: 900;
    width: 50%;
    margin: auto;
    color:hsl(212, 27%, 19%);
}

.first-section-para{
    font-family: 'Barlow', sans-serif;
    font-weight: 500;
    color: hsl(232, 10%, 55%);
    width: 50%;
    margin: 1.5em auto;
    line-height: 25px;
}

.first-section-tag{
    color:hsl(212, 27%, 19%);
    font-family: 'Fraunces', serif;
    font-weight: 900;
    text-decoration: none;
    width: 50%;
    display: block;
    margin: 0 auto;
    border-bottom: 5px solid hsl(51, 100%, 49%);
}

.first-section-second-div{
    background-color: hsl(0, 0%, 100%);
    height: 600px;
    padding-top: 10em;
}

.first-section-third-div , .first-section-fourth-div{
background-image: url("images/desktop/image-graphic-design.jpg");
background-position: center;
background-repeat: no-repeat;
background-size: contain;
width: 720px;
height: 600px;
}

.first-section-fourth-div{
    background-image: url("./images/desktop/image-photography.jpg");
}


.first-section-third-div h3, .first-section-fourth-div h3{
    margin-top: 10em;
}

.first-section-third-div h3, .first-section-third-div p{
    color: hsl(167, 40%, 24%);
}

.first-section-fourth-div h3, .first-section-fourth-div p{
    color: hsl(198, 62%, 26%);
}

/* first section styling ends*/


/* second-section styling starts from here */

.second-section{
    background-color: hsl(51, 98%, 39%);
    position: relative;
}

.second-section h1{
    position: absolute;
    font-family: 'Fraunces', serif;
    text-align: center;
    letter-spacing: 5px;
    font-size: 20px;
    color: hsl(232, 10%, 55%);
    margin: 0;
    padding-top: 4em;
    right:0px;
    left: 0;
    top: -20px;
}

.second-section-container{
    display: flex;
    align-items: center;
    max-width: 1440px;
    text-align: center;
    margin: auto;
    padding: 8em;
    background-color: hsl(0, 0%, 100%);
}

.second-section-inner-div img{
    width: 60px;
    border-radius: 50%;
}

.second-section-inner-div p{
    width: 80%;
    margin: auto;
    font-family: 'Barlow', sans-serif;
    padding: 1em 0;
    line-height: 25px;
}

.second-section-inner-div .client-name{
    font-family: 'Fraunces', serif;
    font-weight: 900;
    margin-bottom: 0;
    padding-bottom: 0;
    color: hsl(212, 27%, 19%);
}

.second-section-inner-div .client-title{
    margin-top: 0;
    padding-top: 0;
    color: hsl(210, 4%, 67%);
}

/* second-section styling ends*/

/* third-section styling starts from here*/

.third-section{
    background-color:hsl(7, 99%, 70%);
}

.third-section-container{
    display: flex;
    align-items: center;
    max-width: 1440px;
    margin: auto;
}

.third-section img{
    width: 100%;
    height: 400px;
    display: block;
    margin: 0 auto;
    object-fit: cover;
}

/* third-section styling ends */

/* footer styling starts from here */

footer{
    background-color: hsl(198, 61%, 40%);
}

.footer-container{
    display: flex;
    align-items: center;
    flex-direction: column;
    max-width: 1440px;
    margin: auto;
    background-color: hsl(168, 53%, 62%);
}

.footer-container h1{
    color: hsl(167, 40%, 24%);
    font-family: 'Fraunces', serif;
    font-weight: 900;
    font-size: 28px;
    margin: 1em auto;
}

.footer-first-div ul{
    display: flex;
    align-items: center;
    list-style: none;
    width: 400px;
    justify-content: space-evenly;
    margin-top: 0;
    margin-bottom: 4em;
}

.footer-first-div ul a {
    text-decoration: none;
    font-family: 'Barlow', sans-serif;
    font-size: 14px;
    color: hsl(167, 40%, 24%);
}

.footer-second-div{
    display:flex;
    align-items: center;
    width: 150px;
    justify-content: space-between;
    margin-bottom: 3em;
}

.my-name{
    background-color: hsl(167, 40%, 24%);
    width: 100%;
    margin: 0 auto;
    text-align: center;
    font-family: 'Fraunces', serif;
    font-weight: 700;
    color: hsl(168, 53%, 62%);
}

.sunnyside-title{
  color: hsl(167, 40%, 24%);
    font-family: 'Fraunces', serif;
    font-weight: 900;
    font-size: 28px;
}
</style>
