<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<nav>
<h1>Pillbox Hill Bean Machine</h1>
<ul>
<li><a href="#menu">Menu</a></li>
<li><a href="#about">About</a></li>
<li><a href="#location">Location</a></li>
</ul>
</nav>
</header>

<section class="hero">
<h2>Fresh Coffee in the Heart of Pillbox Hill</h2>
<p>Specialty beans. Crafted drinks. Chill atmosphere.</p>
<button>View Menu</button>
</section>

<section id="menu" class="menu">
<h2>Popular Drinks</h2>

<div class="menu-grid">

<div class="item">
<h3>Espresso</h3>
<p>Rich double shot</p>
<span>$3</span>
</div>

<div class="item">
<h3>Latte</h3>
<p>Smooth espresso with steamed milk</p>
<span>$4.50</span>
</div>

<div class="item">
<h3>Cold Brew</h3>
<p>Slow brewed for 18 hours</p>
<span>$4</span>
</div>

<div class="item">
<h3>Cappuccino</h3>
<p>Espresso with thick foam</p>
<span>$4</span>
</div>

</div>
</section>

<section id="about" class="about">
<h2>About Us</h2>
<p>
Pillbox Hill Bean Machine is a neighborhood coffee shop serving freshly roasted beans,
handcrafted drinks, and a relaxed atmosphere for locals and visitors.
</p>
</section>

<section id="location" class="location">
<h2>Visit Us</h2>
<p>Pillbox Hill District</p>
<p>Open Daily: 7AM – 7PM</p>
</section>

<footer>
<p>© 2026 Pillbox Hill Bean Machine</p>
</footer>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#f5f1ea;
color:#333;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#3b2f2f;
color:white;
}

nav ul{
display:flex;
list-style:none;
gap:20px;
}

nav a{
color:white;
text-decoration:none;
}

/* HERO */

.hero{
height:80vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93") center/cover;
color:white;
}

.hero h2{
font-size:48px;
margin-bottom:10px;
}

.hero button{
margin-top:20px;
padding:12px 25px;
border:none;
background:#c69c6d;
color:white;
cursor:pointer;
font-size:16px;
}

/* MENU */

.menu{
padding:80px 10%;
text-align:center;
}

.menu-grid{
margin-top:40px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.item{
background:white;
padding:25px;
border-radius:8px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

/* ABOUT */

.about{
padding:80px 10%;
text-align:center;
background:#eee3d3;
}

/* LOCATION */

.location{
padding:80px 10%;
text-align:center;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
background:#3b2f2f;
color:white;
}