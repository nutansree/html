<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            text-align: center;
            margin: 0;
        }

        header nav ul {
            list-style: none;
            text-align: center;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }

        .hero-section {
            background: #f4f4f4;
            padding: 50px 0;
            text-align: center;
        }

        .hero-section h2 {
            margin-bottom: 20px;
        }

        .hero-section p {
            font-size: 1.1em;
        }

        .about-section, .portfolio-section, .contact-section {
            padding: 50px 0;
            text-align: center;
        }

        .about-section p {
            font-size: 1.1em;
            margin-top: 20px;
        }

        .portfolio-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .portfolio-item {
            flex: 1 1 calc(33.333% - 20px);
            margin: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .portfolio-item img {
            width: 100%;
            height: auto;
        }

        .portfolio-item h3 {
            padding: 10px;
            background: #333;
            color: #fff;
            text-align: center;
        }

        .contact-section form {
            max-width: 600px;
            margin: auto;
        }

        .contact-section label {
            display: block;
            margin: 15px 0 5px;
        }

        .contact-section input, .contact-section textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .contact-section button {
            display: block;
            width: 100%;
            padding: 10px;
            border: none;
            background: #333;
            color: #fff;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
        }

        .contact-section button:hover {
            background: #555;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero-section">
        <div class="container">
            <h2>Welcome to My Portfolio</h2>
            <p>Explore my work and get to know me.</p>
        </div>
    </section>

    <section id="about" class="about-section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I am a creative professional with a passion for design and development. I love to create beautiful and functional websites that provide a great user experience.</p>
        </div>
    </section>

    <section id="portfolio" class="portfolio-section">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <img src="project1.jpg" alt="Project 1">
                    <h3>Project Title 1</h3>
                </div>
                <div class="portfolio-item">
                    <img src="project2.jpg" alt="Project 2">
                    <h3>Project Title 2</h3>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 My Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
