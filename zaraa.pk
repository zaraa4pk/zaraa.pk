<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zaraa.pk – Coming Soon</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Poppins,sans-serif}
body{background:#0f0f14;color:#fff}
header{
  min-height:100vh;
  background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),url('https://images.unsplash.com/photo-1521334884684-d80222895322?auto=format&fit=crop&w=1600&q=80');
  background-size:cover;
  background-position:center;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:20px;
}
.logo{
  font-size:48px;
  font-weight:700;
  letter-spacing:2px;
}
.tagline{
  margin-top:10px;
  font-size:18px;
  color:#f5c26b;
}
.coming{
  margin-top:30px;
  font-size:26px;
  font-weight:600;
}
.countdown{
  display:flex;
  gap:20px;
  margin-top:20px;
}
.box{
  background:#1c1c24;
  padding:15px 20px;
  border-radius:10px;
  min-width:80px;
}
.box h2{color:#f5c26b}
section{
  padding:60px 20px;
  max-width:1200px;
  margin:auto;
}
h2.section-title{
  text-align:center;
  margin-bottom:40px;
  font-size:32px;
}
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:25px;
}
.card{
  background:#1c1c24;
  padding:25px;
  border-radius:16px;
  text-align:center;
  transition:.3s;
}
.card:hover{
  transform:translateY(-6px);
  box-shadow:0 20px 40px rgba(0,0,0,.4);
}
.card h3{
  margin-top:15px;
  color:#f5c26b;
}
footer{
  text-align:center;
  padding:30px;
  background:#08080c;
  color:#aaa;
}
</style>
</head>
<body>

<header>
  <div class="logo">Zaraa.pk</div>
  <div class="tagline">Your Style. Your Store.</div>
  <div class="coming">Luxury Shopping – Coming Soon</div>

  <div class="countdown">
    <div class="box"><h2 id="d">00</h2><p>Days</p></div>
    <div class="box"><h2 id="h">00</h2><p>Hours</p></div>
    <div class="box"><h2 id="m">00</h2><p>Min</p></div>
    <div class="box"><h2 id="s">00</h2><p>Sec</p></div>
  </div>
</header>

<section>
  <h2 class="section-title">Everything in One Place</h2>
  <div class="grid">
    <div class="card"><h3>Men’s Fashion</h3><p>Suits, Shirts, Jackets</p></div>
    <div class="card"><h3>Women’s Fashion</h3><p>Luxury Suits, Dresses, Abayas</p></div>
    <div class="card"><h3>Jewelry</h3><p>Necklaces, Rings, Bangles</p></div>
    <div class="card"><h3>Bags</h3><p>Handbags & Travel Bags</p></div>
    <div class="card"><h3>Shoes</h3><p>Men & Women Footwear</p></div>
    <div class="card"><h3>Watches</h3><p>Premium Timepieces</p></div>
    <div class="card"><h3>Beauty</h3><p>Perfumes & Skincare</p></div>
    <div class="card"><h3>Accessories</h3><p>Wallets, Belts & More</p></div>
  </div>
</section>

<footer>
  © 2026 Zaraa.pk – Pakistan’s Next Luxury Brand
</footer>

<script>
const launchDate = new Date();
launchDate.setDate(launchDate.getDate() + 15); // 15 دن بعد لانچ

function update(){
  const now = new Date().getTime();
  const d = launchDate - now;
  if(d < 0) return;
  document.getElementById("d").innerText = Math.floor(d/(1000*60*60*24));
  document.getElementById("h").innerText = Math.floor((d%(1000*60*60*24))/(1000*60*60));
  document.getElementById("m").innerText = Math.floor((d%(1000*60*60))/(1000*60));
  document.getElementById("s").innerText = Math.floor((d%(1000*60))/1000);
}
setInterval(update,1000);
</script>

</body>
</html>
