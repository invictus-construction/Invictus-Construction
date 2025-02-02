<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invictus Construction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin: 5px 0 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 20px;
        }
        nav a:hover {
            background-color: #555;
        }
        main {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        section h2 {
            color: #1a1a1a;
            margin-bottom: 15px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .service {
            flex: 1 1 calc(33.333% - 20px);
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .service img {
            max-width: 100%;
            border-radius: 5px;
        }
        .service h3 {
            margin-top: 15px;
        }
        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Invictus Construction</h1>
    <p>"Building Your Dreams, One Project at a Time!"</p>
</header>

<nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<main>
    <section id="about">
        <h2>About Us</h2>
        <p>At Invictus Construction, we are capable of anything you can think of! From framing new builds to transforming your existing spaces, we bring passion, precision, and expertise to every project. Let us help you turn your vision into reality.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <img src="https://via.placeholder.com/300x200" alt="New Roof">
                <h3>New Roofs</h3>
                <p>Need a new roof? We have you and your house covered!</p>
            </div>
            <div class="service">
                <img src="https://via.placeholder.com/300x200" alt="Bathroom Renovations">
                <h3>Bathroom Renovations</h3>
                <p>We can transform your outdated bathroom into a luxurious retreat!</p>
            </div>
            <div class="service">
                <img src="https://via.placeholder.com/300x200" alt="Kitchen Remodels">
                <h3>Other Renovations</h3>
                <p>Let us bring your dreams to reality, tailored to your needs and style.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have a project in mind? We'd love to hear from you!</p>
        <p>Email: construct.invictus@gmail.com</p>
        <p>Phone: (732) 668-1401</p>
    </section>
</main>

<footer>
    <p>&copy; 2025 Invictus Construction. All rights reserved.</p>
</footer>

</body>
</html>
