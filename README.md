<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>My Portfolio</title>
    <style>
      * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
      }
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #1a1a1a; /* Black */
      }

      header {
        background-color: #4b006e; /* Dark Purple */
        color: white;
        padding: 20px 0;
        text-align: center;
      }

      nav {
        display: flex;
        justify-content: center;
        background-color: #2f004c; /* Darker Purple */
      }

      nav a {
        color: white;
        padding: 14px 20px;
        text-decoration: none;
        text-transform: uppercase;
        transition: background-color 0.3s;
      }

      nav a:hover {
        background-color: #ddd;
        color: black;
      }

      section {
        padding: 40px 10%;
        margin: 20px 0;
        color: white;
      }

      section h2 {
        text-align: center;
        color: #fff;
      }

      .projects {
        display: flex;
        justify-content: space-between;
        flex-wrap: nowrap;           /* Prevent line breaks */
        gap: 20px;
        margin: 0 auto;
        width: 100%;
      }

      .project {
        background-color: #2f2f2f;
        border: 1px solid #ddddddb4;
        padding: 20px;
        width: 35%;                  /* Increased width for images */
        box-sizing: border-box;
        border-radius: 8px;
        text-align: center;
        transition: transform 0.3s;
      }

      .project img {
        object-fit: cover;
        width: 100%;
        height: 250px;               /* Increased height */
        border-radius: 8px;
      }

      .project:hover {
        transform: translateY(-10px);
      }

      @media (max-width: 768px) {
        .project {
          width: 35%;                
        }
      }

      @media (max-width: 480px) {
        .project {
          width: 45%;                
        }
      }

      footer {
        background-color: #4b006e; /* Dark Purple */
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Welcome to My Portfolio</h1>
    </header>

    <nav>
      <a href="#about">About Me</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>

    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello, my name is Italo. I am a web developer passionate about creating
        creative and functional solutions. I have experience in HTML, CSS,
        JavaScript, and other web technologies. My goal is to help businesses and
        individuals build a strong online presence.
      </p>
    </section>

    <section id="services">
      <h2>My Services</h2>
      <div class="projects">
        <div class="project">
          <img src="img/HTML5_logo_and_wordmark.svg.png" alt="HTML5 Logo" />
        </div>
        <div class="project">
          <img src="img/image.png" alt="Service Logo" />
        </div>
        <div class="project">
          <img src="img/javascript-logo-E967E87D74-seeklogo.com.png" alt="JavaScript Logo" />
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        Liked my work? Let's talk! You can find me on social media <a href="https://www.instagram.com/italin__?igsh=bXM5bzNhcnRyYjNu"> Italo galata  </a> or send an
        email directly to <strong>italobgalata@hotmail.com</strong>.
      </p>
    </section>

    
  </body>
</html>
