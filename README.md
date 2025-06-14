<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RD Tile & Stone</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #fdf8f3;
            color: #4b2e2e;
        }
        header {
            background-color: #4b2e2e;
            padding: 20px;
            text-align: center;
        }
        header img {
            height: 80px;
        }
        nav {
            background-color: #6b4b3b;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: auto;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border: 3px solid #b7956b;
            border-radius: 10px;
        }
        footer {
            background-color: #4b2e2e;
            color: #fff;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }
        h1, h2 {
            color: #4b2e2e;
        }
        .button {
            background-color: #b7956b;
            padding: 10px 20px;
            border: none;
            color: white;
            border-radius: 5px;
            font-size: 16px;
            text-decoration: none;
        }
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>

<header>
    <img src="/mnt/data/c89e5476-c8fe-496b-aeb7-29d498ffd205.png" alt="RD Tile & Stone Logo">
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#gallery">Gallery</a>
    <a href="#reviews">Reviews</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h1>Welcome to RD Tile & Stone</h1>
    <p>Transform Your Spaces With Elegant Flooring Solutions.<br>
    Discover a wide selection of porcelain tiles, vinyl flooring, mosaics, and granite countertops.
    </p>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>At RD Tile & Stone, we specialize in bringing quality, style, and durability to your home or business. With a wide variety of flooring and stone products, we help you create beautiful spaces tailored to your unique vision.</p>
</section>

<section id="products">
    <h2>Our Products</h2>
    <ul>
        <li>Porcelain Tiles</li>
        <li>Vinyl Flooring</li>
        <li>Mosaics</li>
        <li>Granite & Quartz Countertops</li>
        <li>Wall Panels</li>
        <li>Blinds & Accessories</li>
    </ul>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/300" alt="Sample 1">
        <img src="https://via.placeholder.com/300" alt="Sample 2">
        <img src="https://via.placeholder.com/300" alt="Sample 3">
    </div>
</section>

<section id="reviews">
    <h2>Customer Reviews</h2>
    <p>"Excellent service and top-quality products! My house looks amazing now. Highly recommended!" – Maria G.</p>
    <p>"Great prices, wide selection, and professional installation." – John D.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@rdtilestone.com</p>
    <p>Phone: (XXX) XXX-XXXX</p>
    <p>Location: Homestead, FL</p>
    <a class="button" href="mailto:info@rdtilestone.com">Email Us</a>
</section>

<footer>
    <p>&copy; 2025 RD Tile & Stone. All rights reserved.</p>
</footer>

</body>
</html>
