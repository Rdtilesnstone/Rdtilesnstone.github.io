<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RD Tile & Stone</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdf8f3;
      color: #4b2e2e;
    }
    header {
      background-color: #4b2e2e;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    header img {
      max-height: 80px;
    }
    nav {
      background-color: #6b4b3b;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      padding: 8px 16px;
    }
    nav a:hover {
      background-color: #b7956b;
      border-radius: 5px;
    }
    .hero {
      background: url('https://via.placeholder.com/1600x500') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
    }
    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 40px;
      color: #4b2e2e;
    }
    .products, .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .products div, .gallery div {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .products div:hover, .gallery div:hover {
      transform: scale(1.05);
    }
    .products img, .gallery img {
      width: 100%;
      display: block;
    }
    .products h3 {
      text-align: center;
      padding: 15px;
      margin: 0;
      background-color: #b7956b;
      color: white;
    }
    form {
      max-width: 600px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea, button {
      padding: 10px;
      font-size: 16px;
    }
    button {
      background-color: #b7956b;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #4b2e2e;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <img src="/mnt/data/c89e5476-c8fe-496b-aeb7-29d498ffd205.png" alt="RD Tile & Stone">
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#products">Products</a>
  <a href="#gallery">Gallery</a>
  <a href="#reviews">Reviews</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
  Elegant Tile & Stone Collections
</div>

<section id="products">
  <h2>Our Products</h2>
  <div class="products">
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Porcelain Tile">
      <h3>Porcelain Tile</h3>
    </div>
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Vinyl Flooring">
      <h3>Vinyl Flooring</h3>
    </div>
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Mosaics">
      <h3>Mosaics</h3>
    </div>
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Granite & Quartz">
      <h3>Granite & Quartz</h3>
    </div>
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Wall Panels">
      <h3>Wall Panels</h3>
    </div>
    <div>
      <img src="https://via.placeholder.com/300x200" alt="Blinds & Accessories">
      <h3>Blinds & Accessories</h3>
    </div>
  </div>
</section>

<section id="gallery">
  <h2>Project Gallery</h2>
  <div class="gallery">
    <div><img src="https://via.placeholder.com/400x300" alt="Project 1"></div>
    <div><img src="https://via.placeholder.com/400x300" alt="Project 2"></div>
    <div><img src="https://via.placeholder.com/400x300" alt="Project 3"></div>
    <div><img src="https://via.placeholder.com/400x300" alt="Project 4"></div>
  </div>
</section>

<section id="reviews">
  <h2>Customer Reviews</h2>
  <p style="text-align:center; max-width:700px; margin:auto;">"RD Tile & Stone helped me completely renovate my kitchen and bathroom. The materials are top-notch and the service was amazing! Highly recommended." – Sarah M.</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Your Message" rows="5" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 RD Tile & Stone. All rights reserved.</p>
</footer>

</body>
</html>
