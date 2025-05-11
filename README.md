<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Colorful Personal Website</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
  
  <!-- Font Awesome for Icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Ubuntu', sans-serif;
      background: linear-gradient(to right, #f953c6, #b91d73);
      color: #fff;
    }

    header {
      background: #00000080;
      padding: 20px 40px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 36px;
      color: #fff;
      letter-spacing: 2px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffde59;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .about {
      background: linear-gradient(135deg, #00c9ff, #92fe9d);
    }

    .services {
      background: linear-gradient(135deg, #f6d365, #fda085);
    }

    .contact {
      background: linear-gradient(135deg, #a1c4fd, #c2e9fb);
      color: #333;
    }

    h2 {
      font-size: 32px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      max-width: 700px;
      margin: 0 auto 20px;
    }

    .service-cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }

    .card {
      background: white;
      color: #333;
      padding: 25px;
      border-radius: 10px;
      width: 250px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card i {
      font-size: 36px;
      margin-bottom: 15px;
      color: #ff4b2b;
    }

    footer {
      background: #222;
      padding: 20px;
      color: #fff;
      text-align: center;
    }

    @media (max-width: 768px) {
      .service-cards {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Colorful World</h1>
    <nav>
      <a href="#about">About Me</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="about" id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Dilkesh, a creative web developer and designer passionate about building beautiful, colorful, and responsive websites for everyone.</p>
  </section>

  <section class="services" id="services">
    <h2>My Services</h2>
    <div class="service-cards">
      <div class="card">
        <i class="fas fa-laptop-code"></i>
        <h3>Web Design</h3>
        <p>Designing modern, vibrant, and responsive websites that stand out.</p>
      </div>
      <div class="card">
        <i class="fas fa-code"></i>
        <h3>Development</h3>
        <p>Developing custom web apps with the latest technologies like HTML, CSS, JS.</p>
      </div>
      <div class="card">
        <i class="fas fa-magic"></i>
        <h3>Graphic Design</h3>
        <p>Creating colorful logos, posters, and branding elements.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Me</h2>
    <p>Email: <strong>dilkeshemail@gmail.com</strong></p>
    <p>Phone: <strong>+1 234 567 890</strong></p>
    <p>Address: 123 Rainbow Lane, Happy City, Colorland</p>
  </section>

  <footer>
    &copy; 2025 Dilkesh | Made with ❤️ and vibrant colors.
  </footer>

</body>
</html>
