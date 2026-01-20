<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>zaraa.pk – Fashion & Style</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --black:#0f0f14;
      --gold:#d4af37;
      --purple:#6b4eff;
      --light:#f7f7fb;
    }
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
    body{background:var(--light);color:#222}
    header{background:linear-gradient(135deg,var(--black),#1c1c2b);padding:24px 60px;display:flex;align-items:center;justify-content:space-between}
    .logo{font-size:28px;font-weight:700;color:var(--gold)}
    nav a{color:#fff;margin-left:28px;text-decoration:none;font-weight:500}
    nav a:hover{color:var(--gold)}

    .hero{padding:90px 60px;background:radial-gradient(circle at top right,#7a5cff,transparent 40%),#0f0f14;color:#fff}
    .hero h1{font-size:52px;font-weight:700;max-width:700px}
    .hero p{margin-top:20px;font-size:18px;max-width:520px;opacity:.9}
    .hero button{margin-top:30px;padding:14px 34px;border:none;border-radius:40px;background:var(--gold);font-size:16px;font-weight:600;cursor:pointer}

    .categories{padding:80px 60px;display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:30px}
    .card{background:#fff;border-radius:22px;padding:30px;box-shadow:0 15px 40px rgba(0,0,0,.08);text-align:center}
    .card h3{margin-top:16px;font-size:20px}
    .card span{color:#777;font-size:14px}

    .products{padding:80px 60px;background:#fff}
    .products h2{text-align:center;font-size:36px;margin-bottom:50px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:28px}
    .product{background:#f9f9fd;border-radius:18px;padding:20px;text-align:center}
    .product img{width:100%;border-radius:14px}
    .product h4{margin:14px 0 6px}
    .product button{margin-top:10px;padding:10px 20px;border:none;border-radius:20px;background:var(--purple);color:#fff;cursor:pointer}

    footer{background:#0f0f14;color:#bbb;padding:40px 60px;margin-top:80px}
    footer .brand{color:var(--gold);font-weight:700;font-size:20px}
    footer p{margin-top:10px;font-size:14px;max-width:400px}
  </style>
</head>
<body>

<header>
  <div class="logo">zaraa.pk</div>
  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">Categories</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Fashion, Jewelry & Accessories – All in One Place</h1>
  <p>Discover premium clothing, bags, shoes, watches, jewelry and accessories curated for modern style.</p>
  <button>Start Shopping</button>
</section>

<section class="categories">
  <div class="card"><h3>Clothing</h3><span>Men • Women • Kids</span></div>
  <div class="card"><h3>Bags</h3><span>Handbags • Backpacks</span></div>
  <div class="card"><h3>Shoes</h3><span>Sneakers • Formal</span></div>
  <div class="card"><h3>Watches</h3><span>Luxury • Casual</span></div>
  <div class="card"><h3>Jewelry</h3><span>Rings • Necklaces</span></div>
  <div class="card"><h3>Accessories</h3><span>Belts • Sunglasses</span></div>
</section>

<section class="products">
  <h2>Trending Products</h2>
  <div class="grid">
    <div class="product"><img src="https://via.placeholder.com/300x220"><h4>Luxury Watch</h4><span>PKR 12,999</span><button>Add to Cart</button></div>
    <div class="product"><img src="https://via.placeholder.com/300x220"><h4>Designer Bag</h4><span>PKR 8,500</span><button>Add to Cart</button></div>
    <div class="product"><img src="https://via.placeholder.com/300x220"><h4>Gold Ring</h4><span>PKR 22,000</span><button>Add to Cart</button></div>
    <div class="product"><img src="https://via.placeholder.com/300x220"><h4>Stylish Sneakers</h4><span>PKR 6,999</span><button>Add to Cart</button></div>
  </div>
</section>

<footer>
  <div class="brand">zaraa.pk</div>
  <p>zaraa.pk is a modern Pakistani fashion & lifestyle marketplace offering premium quality products with trusted service.</p>
</footer>

</body>
</html>
