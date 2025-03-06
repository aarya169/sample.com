# sample.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS -->
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to My Website</h1>
        <p>This is a simple website example.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Learn more about our services and team.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Web Design</li>
            <li>Web Development</li>
            <li>SEO Optimization</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 My Simple Website</p>
    </footer>

    <script src="script.js"></script> <!-- Link to external JavaScript -->
</body>
</html>
