<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NMZ – Non-Military Zone | Official Masterplan</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
:root {
  --navy:#001d3d;
  --gold:#d4af37;
  --light:#f4f7f6;
}

body{
  margin:0;
  font-family:Segoe UI, Arial, sans-serif;
  background:var(--light);
  color:#333;
}

header{
  background:
    linear-gradient(rgba(0,29,61,.85),rgba(0,29,61,.85)),
    url("https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1500&q=80");
  background-size:cover;
  background-position:center;
  color:#fff;
  text-align:center;
  padding:80px 20px;
  border-bottom:8px solid var(--gold);
}

.container{
  max-width:1000px;
  margin:auto;
  padding:25px;
}

.card{
  background:#fff;
  border-radius:15px;
  overflow:hidden;
  margin-bottom:30px;
  box-shadow:0 8px 20px rgba(0,0,0,.1);
  border-top:5px solid var(--gold);
}

.visual-box{
  height:200px;
  background-size:cover;
  background-position:center;
}

.card-body{ padding:25px; }

.dual-lang{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:20px;
}

.en{
  border-left:3px solid var(--gold);
  padding-left:15px;
}

.he{
  direction:rtl;
  text-align:right;
  border-right:3px solid var(--navy);
  padding-right:15px;
}

h2{ color:var(--navy); margin-top:0; }

.infra{
  background:var(--navy);
  color:#fff;
  padding:40px 20px;
  border-radius:15px;
  text-align:center;
}

.tags{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:10px;
  margin-top:20px;
}

.tag{
  border:1px solid var(--gold);
  padding:8px 15px;
  border-radius:5px;
  font-weight:bold;
}

footer{
  text-align:center;
  padding:30px;
  font-size:.85rem;
  color:#777;
}

@media(max-width:768px){
  .dual-lang{ grid-template-columns:1fr; }
}
</style>
</head>

<body>

<header>
  <h1>NMZ MASTERPLAN</h1>
  <p style="color:var(--gold);font-weight:bold;">
    FREE ECONOMIC ZONE – ISRAEL · SYRIA · LEBANON
  </p>
</header>

<div class="container">

<div class="card">
  <div class="visual-box" style="background-image:url('https://images.unsplash.com/photo-1554469384-e58fb16e293a?auto=format&fit=crop&w=800&q=60');"></div>
  <div class="card-body">
    <div class="dual-lang">
      <div class="en">
        <h2><i class="fas fa-landmark"></i> Global Finance</h2>
        <p>International banking hub with tax-free status and multi-currency exchange.</p>
      </div>
      <div class="he">
        <h2>מרכז פיננסי עולמי</h2>
        <p>מוקד בנקאות בינלאומי עם פטור ממס ובורסה רב-מטבעית.</p>
      </div>
    </div>
  </div>
</div>

<div class="card">
  <div class="visual-box" style="background-image:url('https://images.unsplash.com/photo-1541888946425-d81bb193005f?auto=format&fit=crop&w=800&q=60');"></div>
  <div class="card-body">
    <div class="dual-lang">
      <div class="en">
        <h2><i class="fas fa-building"></i> RCC Infrastructure</h2>
        <p>Reinforced concrete construction for hospitals, clinics and education hubs.</p>
      </div>
      <div class="he">
        <h2>תשתיות RCC</h2>
        <p>מבני בטון מזוין לבתי חולים, מרפאות ומרכזי חינוך.</p>
      </div>
    </div>
  </div>
</div>

<div class="infra">
  <h2>STRATEGIC CONNECTIVITY</h2>
  <div class="tags">
    <div class="tag">HAIFA RAIL</div>
    <div class="tag">SYRIAN PORTS</div>
    <div class="tag">BEIRUT LINK</div>
    <div class="tag">ARABIAN HIGHWAY</div>
  </div>
</div>

</div>

<footer>
  NMZ PROJECT — CONFIDENTIAL DEVELOPMENT © 2026
</footer>

</body>
</html>
