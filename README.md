<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Illuminated Designs</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo">
                <h1>Illuminated Designs</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
        <section class="hero">
            <div class="hero-text">
                <h2>Transform Your Space with Elegance and Style</h2>
                <p>We bring light and life into your interior spaces</p>
            </div>
        </section>
    </header>

    <main>
        <section id="about" class="about">
            <div class="about-content">
                <h2>About Us</h2>
                <p>At Illuminated Designs, we specialize in creating beautiful and functional interiors. Our team of experts uses the latest trends and timeless designs to transform your space into a place of beauty and comfort.</p>
            </div>
        </section>

        <section id="services" class="services">
            <h2>Our Services</h2>
            <div class="services-list">
                <div class="service-item">
                    <img src="images/service1.jpg" alt="Lighting Design">
                    <h3>Lighting Design</h3>
                    <p>We design lighting solutions that enhance the atmosphere and functionality of your space.</p>
                </div>
                <div class="service-item">
                    <img src="images/service2.jpg" alt="Interior Styling">
                    <h3>Interior Styling</h3>
                    <p>Transform your interiors with our expert styling services, combining colors, textures, and furnishings.</p>
                </div>
                <div class="service-item">
                    <img src="images/service3.jpg" alt="Renovation">
                    <h3>Renovation</h3>
                    <p>We offer complete renovation services, from planning to execution, to create your dream interior.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Illuminated Designs | All Rights Reserved</p>
    </footer>
</body>
</html>