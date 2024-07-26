<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Brooklyn Brit</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            color: black;
        }
        header {
            background-color: red;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: blue;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            max-width: 300px;
            margin: 10px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        footer {
            background-color: blue;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .social-links a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>The Brooklyn Brit</h1>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
    </ul>
</nav>

<div id="home" class="container">
    <h2>Welcome to The Brooklyn Brit</h2>
    <p>We provide top-notch consulting services to help you achieve your business goals.</p>
</div>

<div id="about" class="container">
    <h2>About Us</h2>
    <p>The Brooklyn Brit offers a range of consulting services tailored to your needs. With years of experience and a commitment to excellence, we help businesses succeed.</p>
</div>

<div id="projects" class="container">
    <h2>Projects</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/300" alt="Project 1">
        <img src="https://via.placeholder.com/300" alt="Project 2">
        <img src="https://via.placeholder.com/300" alt="Project 3">
    </div>
</div>

<div id="contact" class="container">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/{your-form-id}" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" required></textarea><br>
        <button type="submit">Send</button>
    </form>
</div>

<footer>
    <p>&copy; 2024 The Brooklyn Brit. All rights reserved.</p>
    <div class="social-links">
        <a href="https://facebook.com">Facebook</a>
        <a href="https://twitter.com">Twitter</a>
        <a href="https://linkedin.com">LinkedIn</a>
    </div>
</footer>

</body>
</html>
