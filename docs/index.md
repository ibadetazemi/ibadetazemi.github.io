<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ibadetazemi.github.io</title>
    <link rel="stylesheet" href="style.css1" />
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.14.0/css/all.css"
      integrity="sha384-HzLeBuhoNPvSl5KYnjx0BT+WB0QEEqLprO+NBkkk5gbc67FTaL7XIGa2w1L0Xbgc"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <!-- Navbar Section -->
    <nav class="navbar">
      <div class="navbar__container">
        <a href="#home" id="navbar__logo">Ibadet Azemi</a>
        <div class="navbar__toggle" id="mobile-menu">
          <span class="bar"></span> <span class="bar"></span>
          <span class="bar"></span>
        </div>
        <ul class="navbar__menu">
          <li class="navbar__item">
            <a href="#home" class="navbar__links" id="home-page">Home</a>
          </li>
          <li class="navbar__item">
            <a href="#about" class="navbar__links" id="about-page">About</a>
          </li>
          <li class="navbar__item">
            <a href="#services" class="navbar__links" id="services-page"
              >Services</a
            >
          </li>
          <li class="navbar__btn">
            <a href="#sign-up" class="button" id="signup">Contact</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero" id="home">
      <div class="hero__container">
        <h1 class="hero__heading">Web Developer<span></span></h1>
        <h1 class="hero__heading"><span>UX/UI Designer</span></h1>
        <p class="hero__description"></p>
        <button class="main__btn"><a href="#">><</a></button>
      </div>
    </div>

    <!-- About Section -->
    <div class="main" id="about">
      <div class="main__container">
        <div class="main__img--container">
          <img src="IMG-8691.jpg"=" width= "400">
          <div class="main__img--card"><i class="fas fa-layer-group"></i></div>
        </div>
        <div class="main__content">
          <h1>What do I do?</h1>
          <h2>(CSS, HTML, JAVASCRIPT & PYTHON) + UX/UI Design</h2>
          <p>Schedule a call to learn more about my services</p>
          <button class="main__btn"><a href="#">Schedule Call</a></button>
        </div>
      </div>
    </div>

    <!-- Services Section -->
    <div class="services" id="services">
      <h1>My Services</h1>
      <div class="services__wrapper">
        <div class="services__card">
          <h2>UX/UI Design</h2>
          <p>Figma + Adobe XD</p>
          <div class="services__btn"><button>><</button></div>
        </div>
        <div class="services__card">
          <h2>Web Development</h2>
          <p>HTML/CSS/JS</p>
          <div class="services__btn"><button>><</button></div>
        </div>
        <div class="services__card">
          <h2>Python</h2>
          <p>Backend Development</p>
          <div class="services__btn"><button>><</button></div>
        </div>
        <div class="services__card">
          <h2>Art</h2>
          <p>Oil, Pencil, Graphic Design, Fashion Design, Music</p>
          <div class="services__btn"><button>><</button></div>
        </div>
      </div>
    </div>

    <!-- Features Section -->
    <div class="main" id="sign-up">
      <div class="main__container">
        <div class="main__content">
          <h1>Get Creative Help Today</h1>
          <h2>HTML, CSS, JAVASCRIPT + UX/UI Design - Art</h2>
          <p>My passion for art and technology have taken me to different heights come see.</p>
          <button class="main__btn"><a href="#">Contact</a></button>
        </div>
        <div class="main__img--container">
          <div class="main__img--card" id="card-2">
            <i class="fas fa-users"></i>
          </div>
        </div>
      </div>
    </div>


  <script type="text/javascript" src="script.js"></script>
</body>
</html>  

    <!-- Footer Section -->
    <div class="footer__container">
      <div class="footer__links">
        <div class="footer__link--wrapper">
          <div class="footer__link--items">
            <h2>About Me</h2>
            <a href="/sign__up">How it works</a> <a href="/">Testimonials</a>
            <a href="/">Careers</a> <a href="/">Terms of Service</a>
          </div>
          <div class="footer__link--items">
            <h2>Contact</h2>
            <a href="">Contact</a> <a href="/">Support</a>
            <a href="/">Destinations</a>
          </div>
        </div>
        <div class="footer__link--wrapper">
          <div class="footer__link--items">
            <h2>Videos</h2>
            <a href="/">Submit Video</a> <a href="/">Ambassadors</a>
            <a href="/">Agency</a>
          </div>
          <div class="footer__link--items">
            <h2>Social Media</h2>
            <a href="https://www.instagram.com/?hl=en">Instagram</a> <a href="https://www.facebook.com/">Facebook</a>
            <a href="https://www.youtube.com/">Youtube</a> <a href="https://twitter.com/?lang=en">Twitter</a>
          </div>
        </div>
      </div>
      <section class="social__media">
        <div class="social__media--wrap">
          <div class="footer__logo">
            <a href="/" id="footer__logo">Ibadet Azemi</a>
          </div>
          <p class="website__rights">© Ibadet Azemi 2022. All rights reserved</p>
          <div class="social__icons">
            <a href="https://www.facebook.com/" class="social__icon--link" target="_blank"
              ><i class="fab fa-facebook"></i
            ></a>
            <a href="https://www.instagram.com/?hl=en" class="social__icon--link"
              ><i class="fab fa-instagram"></i
            ></a>
            <a href="https://www.youtube.com/" class="social__icon--link"
              ><i class="fab fa-youtube"></i
            ></a>
            <a href="https://www.linkedin.com/in/ibadet-ivy-azemi-96192a197" class="social__icon--link"
              ><i class="fab fa-linkedin"></i
            ></a>
            <a href="https://twitter.com/?lang=en" class="social__icon--link"
              ><i class="fab fa-twitter"></i
            ></a>
          </div>
        </div>
      </section>
    </div>

    <script src="app.js"></script>
  </body>
</html>
