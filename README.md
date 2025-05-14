<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Happy Dogo</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap"
      rel="stylesheet"
    />
    <style>#hero {
  background-position: 100%;
    background: rgb(4, 0, 6);
  background: linear-gradient(
    63deg,
    rgba(4, 0, 6, 1) -2%,
    rgba(68, 0, 95, .9) 112%
  );
  padding-top: 100px;
}
.hero {
    gap: 50px;
}
.gradient-background {
  flex: 1 1 auto;
 height: 635px;
  width: 515px;
  border-radius: 240px 240px 1px 1px;
  background: linear-gradient(30.59deg, #140119 1.55%, #5b0e4e 88.54%);
  box-shadow: 0px 4px 250px 0px #ffc93e40;
 position: relative;
}
.text-container {
 max-width: 516px;
  flex-direction: column;
  gap: 30px;
  .call {
    align-items: center;
    gap: 30px;
    margin-top: 40px;
    .btn {
        text-align: center;
        text-decoration: none;
        line-height: 48px;
      width: 160px;
      height: 48px;
      border-radius: 40px;
      background: rgb(255, 90, 55);
      background: linear-gradient(
        54deg,
        rgba(255, 90, 55, 1) 100%,
        rgba(255, 55, 120, 1) 100%
         );
      cursor: pointer;
    }
    .btn:hover {
      -webkit-box-shadow: 0px 0px 20px 1px rgba(209,88,88,1);
-moz-box-shadow: 0px 0px 20px 1px rgba(209,88,88,1);
box-shadow: 0px 0px 20px 1px rgba(209,88,88,1);
    }
  }
}
.image-container {
   max-width: 515px;
   .dogs {
    flex-shrink: 1;
    flex-grow: 1;
    flex-basis: auto;
   }
 
.dog {
  overflow: hidden;
    position: absolute;
    bottom: 0;
}
  .dog1 {
    position: absolute;
    left: 40px;
    top: -20px;
  }
  .dog2 {
    position: absolute;
    top: 160px;
    left: 15px;
  }
  .dog3 {
    position: absolute;
    top: 5px;
    right: 90px;
  }
  .dog4 {
    position: absolute;
    top: 120px;
    right: -10px;
  }
  .dog5 {
    position: absolute;
    bottom: 100px;
    left: -25px;
  }

}
@media only screen and (max-width: 1100px) {
    .hero {
        flex-direction: column;
        align-items: center;
        justify-content: center;  
    } 
    }</style>
  </head>
  <body>
    <header>
      <div class="background">
        <div class="container">
          <nav class="navigation flex">
            <div class="logo flex">
              <a href="/"><img src="./assets/logo.png" alt="petty logo" /></a>
            </div>
            <ul class="middle-list flex inter-w400 text-sm">
              <li><a href="#">Home</a></li>
              <li><a href="#">About</a></li>
              <li><a href="#">Services</a></li>
              <li><a href="#">Training</a></li>
              <li><a href="#">Shop</a></li>
            </ul>
            <div class="inter-w500 text-sm contact-us flex">
              <a class="flex" href="mailto:Happydoggo@email.com"
                >Contact us<img
                  src="./assets/arrow-right-circle-fill.png"
                  alt="arrow"
              /></a>
            </div>
          </nav>
        </div>
      </div>
    </header>
    <section id="hero">
      <div class="container hero flex">
        <div class="text-container flex">
          <p class="text-m text-gradient inter-w600">Welcome...</p>
          <h1 class="text-xxl inter-w300 text-white">
            Warmth and comfort for
            <span class="text-xxl text-gradient inter-w800"
              >your furry friends</span
            >
          </h1>
          <p class="inter-w300 text-sm text-white">
            Discover the perfect pet heating solutions to keep your beloved
            companions cozy and content all year round.
          </p>
          <div class="call flex">
            <a class="btn text-xs text-white inter-w300" href="">Our services</a>
            <a class="text-white text-xs inter-w300" href="tel:+37060000000"
              >Schedule a call</a>
          </div>
        </div>
        <div class="image-container flex">
          <div class="gradient-background">
            <img class="dog" src="./assets/dog_img.png" alt="" />
            <img class="dog1" src="./assets/dog1.png" alt="" />
            <img class="dog2" src="./assets/dog2.png" alt="" />
            <img class="dog3" src="./assets/dog3.png" alt="" />
            <img class="dog4" src="./assets/dog4.png" alt="" />
            <img class="dog5" src="./assets/dog5.png" alt="" />
          </div>
        </div>
      </div>
    </section>
  </body>
</html>
