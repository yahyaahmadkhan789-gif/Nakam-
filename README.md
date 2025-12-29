# Nakam-
Nakam – Desi streetwear for the city rebel. Quality hoodies, tees, and vibes that speak louder than words.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StreetWear Shop</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, sans-serif; }
    body { background: #111; color: #fff; }
    header { padding: 20px; display: flex; justify-content: space-between; align-items: center; background: #000; }
    header h1 { font-size: 24px; }
    nav a { color: #fff; margin-left: 15px; text-decoration: none; }
    .hero { padding: 60px 20px; text-align: center; background: linear-gradient(135deg, #000, #222); }
    .hero h2 { font-size: 40px; margin-bottom: 10px; }
    .hero p { opacity: 0.8; }
    .products { padding: 40px 20px; display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; }
    .card { background: #1c1c1c; border-radius: 10px; padding: 15px; text-align: center; }
    .card img { width: 100%; border-radius: 8px; }
    .card h3 { margin: 10px 0; }
    .card button { background: #fff; color: #000; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #000; margin-top: 40px; opacity: 0.7; }
  </style>
</head>
<body>

<header>
  <h1>StreetWear</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#products">Shop</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Desi Streetwear</h2>
  <p>Premium Hoodies & T‑Shirts</p>
</section>

<section class="products" id="products">
  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Hoodie" />
    <h3>Black Hoodie</h3>
    <p>PKR 3,999</p>
    <button>Add to Cart</button>
  </div>
  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Tshirt" />
    <h3>White T‑Shirt</h3>
    <p>PKR 1,999</p>
    <button>Add to Cart</button>
  </div>
  <div class="card">
    <img src="https://via.placeholder.com/300" alt="Hoodie" />
    <h3>Oversized Hoodie</h3>
    <p>PKR 4,499</p>
    <button>Add to Cart</button>
  </div>
</section>

<footer>
  © 2025 StreetWear. All rights reserved.
</footer>

</body>
</html>
