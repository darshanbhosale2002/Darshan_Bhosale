<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darshan Bhosale | Operations Manager</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Darshan Bhosale</h1>
            <p>Operations Manager | Optimizing Processes, Driving Efficiency</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I’m Darshan Bhosale, a dedicated Operations Manager specializing in optimizing supply chain processes, reducing costs, and enhancing productivity. With a strong academic background in BBA and an MBA in Operations and Supply Chain Management, I bring both strategic and practical expertise to every project.</p>
        </div>
    </section>

    <section id="testimonials">
        <div class="container">
            <h2>What People Say</h2>
            <div class="testimonial">
                <p>“Darshan's exceptional ability to streamline operations and manage supply chains transformed our business efficiency. Highly recommended!”</p>
                <h4>- John Doe, CEO of Tech Innovations</h4>
            </div>
            <div class="testimonial">
                <p>“A true professional with a sharp eye for process improvement. Darshan's strategies significantly reduced our operational costs.”</p>
                <h4>- Jane Smith, Manager at Green Logistics</h4>
            </div>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <p>Here are some highlights of my work:</p>
            <ul>
                <li>Implemented lean management techniques, saving 20% in operational costs.</li>
                <li>Managed end-to-end supply chain processes for multiple industries.</li>
                <li>Developed and executed strategies for sustainable business operations.</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>If you'd like to discuss how I can help your business, feel free to reach out!</p>
            <form>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Darshan Bhosale. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Header Section */
header {
    background: #444;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

/* Navigation Bar */
nav {
    background: #222;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Section Styles */
section {
    padding: 20px 0;
}

section h2 {
    color: #444;
    text-align: center;
    margin-bottom: 10px;
}

/* Testimonials */
.testimonial {
    background: #f4f4f4;
    padding: 15px;
    margin: 15px 0;
    border-left: 5px solid #444;
}

/* Form Styles */
form label {
    display: block;
    margin: 10px 0 5px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ddd;
}

form button {
    display: inline-block;
    background: #444;
    color: #fff;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

form button:hover {
    background: #333;
}

/* Footer */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}
