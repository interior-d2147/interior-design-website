<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interior Design by [Your Name]</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 50px 20px;
            text-align: center;
        }
        section h2 {
            font-size: 36px;
            color: #333;
        }
        .services, .portfolio, .contact {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .service, .portfolio-item {
            margin: 20px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        .portfolio-item img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Interior Design by [Your Name]</h1>
        <p>Your dream space, designed with care and creativity.</p>
    </header>

    <nav>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>Residential Design</h3>
                <p>We create beautiful and functional living spaces tailored to your style and needs.</p>
            </div>
            <div class="service">
                <h3>Commercial Design</h3>
                <p>Designing professional and inviting office spaces, retail stores, and more.</p>
            </div>
            <div class="service">
                <h3>Space Planning</h3>
                <p>Optimizing the layout of any space to ensure functionality and aesthetic appeal.</p>
            </div>
        </div>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Project 1">
                <h3>Modern Living Room</h3>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Project 2">
                <h3>Cozy Bedroom</h3>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Project 3">
                <h3>Elegant Office Space</h3>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact">
            <p>If you're interested in our services, feel free to reach out!</p>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Interior Design by [Your Name]. All rights reserved.</p>
    </footer>

</body>
</html>