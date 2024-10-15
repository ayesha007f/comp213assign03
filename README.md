<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Procreate - Unleash Your Creativity</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            width: 980px;
            margin: 0 auto;
        }
        header {
            position: relative;
            height: 300px; /* Adjust the height based on the image size */
            background: url('https://css-tricks.com/wp-content/uploads/2020/01/procreate-logo.png') no-repeat center center;
            background-size: cover;
            text-align: center;
            color: white;
        }
        header h1 {
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 2.5em;
            font-weight: bold;
        }
        nav {
            position: absolute;
            bottom: 20px;
            width: 100%;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            padding: 10px 15px;
            background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background for better visibility */
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: rgba(255, 255, 255, 0.3);
        }
        h2, h3 {
            text-align: center;
        }
        #about-section, #products-section, #hotspots-section {
            padding: 20px;
            border-bottom: 1px solid #ddd;
        }
        .image-container {
            display: flex;
            justify-content: space-around;
            padding: 10px;
        }
        .product-image {
            width: 300px;
            height: 200px;
            background-color: #ddd;
        }
        footer {
            text-align: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Procreate - Unleash Your Creativity</h1>
        <nav>
            <a href="#about-section">Home</a>
            <a href="#about-section">About</a>
            <a href="#products-section">Products</a>
            <a href="#hotspots-section">Hot Spots</a>
            <a href="#procreate">Procreate</a>
        </nav>
    </header>

    <section id="about-section">
        <h2>About Us</h2>
        <p>Learn more about Procreate and what it has to offer!</p>
        <h3>Digital Art Tool</h3>
        <p>Procreate is a powerful, intuitive digital illustration app created by Savage Interactive, designed for artists on the go. It has revolutionized the way artists create on the iPad, offering a robust set of features that rival desktop-grade software. In 2016, Procreate became one of the top ten best-selling iPad apps on the App Store.</p>
        <h3>Features</h3>
        <p>Procreate offers a variety of features like brushes, layers, time-lapse recording, and more, making it a versatile tool for beginners and professionals alike. Within the Procreate application, animation capabilities are present. The process involves sketching individual frames or layers, selectively concealing all but the desired initial frame. Users get more control and range over their stabilization in a brush’s setting or though preference settings under pressure and smoothing for global affects.</p>
    </section>

    <section id="products-section">
        <h2>Products</h2>
        <div class="product">
        <h3>Procreate App</h3>
        <img src="https://example.com/path-to-procreate-image.jpg" alt="Procreate App" width="300" />
        <p>Procreate is a powerful drawing app for iPad that allows artists to create stunning artwork. With a wide range of brushes and tools, it's perfect for both beginners and professionals.</p>
        <a href="Details.html">Learn More</a>
    </div>
    <div class="product">
        <h3>Procreate Brushes</h3>
        <img src="https://example.com/path-to-brushes-image.jpg" alt="Procreate Brushes" width="300" />
        <p>Enhance your Procreate experience with high-quality brushes designed for various art styles.</p>
        <a href="Details.html">Learn More</a>
    </div>
    <div class="product">
        <h3>Procreate Courses</h3>
        <img src="https://example.com/path-to-courses-image.jpg" alt="Procreate Courses" width="300" />
        <p>Join online courses to master Procreate and unleash your creativity!</p>
        <a href="Details.html">Learn More</a>
        </div>
    </section>

    <section id="hotspots-section">
        <h2>Local Hot Spots</h2>
        <p>Start Your Journey Here:</p>
        <ul>
            <li><a href="https://www.apple.com/ca/">Apple Store Canada</a></li>
            <li><a href="https://www.bestbuy.ca/">Best Buy Canada</a></li>
            <li><a href="https://www.savageinteractive.com/">Savage Interactive</a></li>
        </ul>
    </section>

    <footer>
        <p>© 2024 Ayesha Fatima | Student Number: 301477527 | Assignment 3 - Procreate</p>
        <p>Image and information credits: Apple Store Canada, Best Buy, Savage Interactive.</p>
    </footer>
</body>
</html>
