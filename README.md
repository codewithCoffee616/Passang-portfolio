# Passang-portfolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
    <script
      src="https://kit.fontawesome.com/7a4b62b0a4.js"
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <header>
      <nav class="container">
        <div class="logo">Portfolio</div>
        <ul>
          <a href="#hero">
            <li>Home</li>
          </a>
          <a href="#project">
            <li>Projects</li>
          </a>
          <a href="#contact">
            <li>Contact</li>
          </a>
        </ul>
      </nav>
    </header>
    <main>
      <section id="hero">
        <div class="container">
          <div class="hero_image animate__animated animate__bounceInLeft">
            <img src="me.jpg" alt="hero image"style="width: 300px; height: auto; border: 2px solid #000; margin: 20px;border-radius:50%">
          </div>
          <div class="hero_content">
            <h1>
              <span class="hi_text">Hi</span> , I am
              <span class="name_text">Passang landup sherpa</span>
            </h1>
            <h2>Frontend Developer</h2>
          </div>
        </div>
      </section>
      <section id="project">
        <h2>PROJECTS</h2>
        <div class="container">
          <div class="project_container">
            <div class="grid_item">
              <div class="card">
                <img src="shop.png" alt="Project 1" />
                <div class="card_content">
                  <h3>Shopping website</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="news.jpg" alt="Project 1" />
                <div class="card_content">
                  <h3>Sikkim New's</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="music.jpg" alt="Project 1" />
                <div class="card_content">
                  <h3>Music</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="form.jpg" alt="Project 4" />
                <div class="card_content">
                  <h3>Form Application</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="job.jpg" alt="Project 5" />
                <div class="card_content">
                  <h3>Job Application</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="photo.jpg" alt="Project 6" />
                <div class="card_content">
                  <h3>imgSlider Gallery</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="parallax.jpg" alt="Project 7" />
                <div class="card_content">
                  <h3>Parallax website</h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="restaurant.jpg" alt="Project 8" />
                <div class="card_content">
                  <h3>Restaurant Website </h3>
                </div>
              </div>
            </div>
            <div class="grid_item">
              <div class="card">
                <img src="images/project9.png" alt="Project 9" />
                <div class="card_content">
                  <h3>Blog Website</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="contact">
        <div class="container">
          <h2>Let's work together...</h2>
          <div class="top_contact">
            <div class="contact_way">
              <i class="fab fa-linkedin"></i>
              <h3>Linkedin</h3>
            </div>
            <div class="contact_way">
              <i class="fa fa-twitter"></i>
              <h3>Twitter</h3>
            </div>
            <div class="contact_way">
              <h3>@ Send Mail</h3>
            </div>
          </div>
          <div class="bottom_contact">
            <div class="contact_way">
              <i class="fab fa-github"></i>
              <h3>Github</h3>
            </div>
            <div class="contact_way">
              <i class="fa fa-mobile"></i>
              <h3>Mobile</h3>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer>
      <div class="container">Created By Do Some Coding Channel</div>
    </footer>
  </body>
</html>
