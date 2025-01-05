<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Example Design for GitHub Repository Readme File</title>
  <style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: #FFE5D4; /* Warm pastel peach */
      color: #333;
      line-height: 1.6;
      overflow-x: hidden;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header */
    header {
      background-color: #FF7F50; /* Coral color */
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header nav {
      margin-top: 10px;
    }

    header nav a {
      margin: 0 15px;
      color: white;
      font-weight: bold;
      font-size: 1.1rem;
    }

    header nav a:hover {
      text-decoration: underline;
    }

    /* Hero Section */
    .hero {
      background-color: #FFA07A; /* Light Salmon */
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      font-size: 2.2rem;
    }

    .hero p {
      font-size: 1.2rem;
      margin: 20px 0;
    }

    .hero button {
      background-color: #FF4500; /* Orange Red */
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }

    .hero button:hover {
      background-color: #E03E00;
    }

    /* Main Content */
    main {
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
    }

    section h3 {
      text-align: center;
      font-size: 1.8rem;
      color: #FF7F50;
      margin-bottom: 20px;
    }

    section p {
      max-width: 800px;
      margin: 0 auto 20px;
      text-align: center;
    }

    /* Services Section */
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .service-item {
      background-color: white;
      border: 1px solid #FF7F50;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      width: 300px;
      transition: transform 0.3s;
    }

    .service-item:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .service-item h4 {
      color: #FF4500;
      margin-bottom: 10px;
    }

    /* Footer */
    footer {
      background-color: #FF4500;
      color: white;
      text-align: center;
      padding: 20px;
    }

    footer p {
      margin-bottom: 10px;
    }

    footer a {
      color: #FFE5D4;
      font-weight: bold;
    }

    footer a:hover {
      text-decoration: underline;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .hero h2 {
        font-size: 1.8rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .services {
        flex-direction: column;
        align-items: center;
      }

      .service-item {
        width: 90%;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Example Design for GitHub Repository Readme File</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <div class="hero">
    <h2>Welcome to Example Design</h2>
    <p>
      This is a warm-themed webpage designed for showcasing simple, clean layouts for GitHub repositories and beyond!
    </p>
    <button>Learn More</button>
  </div>

  <!-- Main Content -->
  <main>
    <!-- About Section -->
    <section id="about">
      <h3>About Us</h3>
      <p>
        Example Design is a creative agency that specializes in crafting beautiful designs and user-friendly interfaces.
        We aim to make the web a more visually appealing and functional space.
      </p>
    </section>

    <!-- Services Section -->
    <section id="services">
      <h3>Our Services</h3>
      <div class="services">
        <div class="service-item">
          <h4>Web Design</h4>
          <p>We design responsive, aesthetic, and user-friendly websites tailored to your needs.</p>
        </div>
        <div class="service-item">
          <h4>Graphic Design</h4>
          <p>Our team creates stunning visuals for branding, marketing, and social media campaigns.</p>
        </div>
        <div class="service-item">
          <h4>UX/UI Consulting</h4>
          <p>We help optimize your website or app to enhance user experience and engagement.</p>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h3>Contact Us</h3>
      <p>Have a project in mind? We'd love to hear from you!</p>
      <p>Email: <a href="mailto:example@design.com">example@design.com</a></p>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p>© 2025 Example Design. All Rights Reserved.</p>
    <p>
      Follow us on <a href="#">Twitter</a> | <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>