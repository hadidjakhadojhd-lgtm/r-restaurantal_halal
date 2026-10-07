<!doctype html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>R-Restaurant Al Halal</title>

<style>
*{box-sizing:border-box}

body{
margin:0;
font-family:Arial,sans-serif;
background:#fffaf3;
color:#222
}

header{
background:#173b2b;
color:white;
padding:20px 7%;
display:flex;
justify-content:space-between;
align-items:center
}

header strong{
font-size:22px
}

nav a{
color:white;
margin:10px;
text-decoration:none
}

.hero{
text-align:center;
padding:90px 7%;
background:#24583f;
color:white
}

.hero h1{
font-size:44px
}

.btn{
display:inline-block;
background:#e5a83b;
color:#222;
padding:13px 22px;
border-radius:8px;
text-decoration:none;
font-weight:bold
}

.section{
padding:50px 7%;
max-width:1100px;
margin:auto
}

h2{
text-align:center;
color:#173b2b
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px
}

.card{
background:white;
padding:22px;
border-radius:14px;
box-shadow:0 5px 20px #0001
}

.price{
font-weight:bold;
color:#a36d12
}

.contact{
background:#173b2b;
color:white;
text-align:center
}

.contact h2{
color:white
}

footer{
text-align:center;
background:#10281e;
color:white;
padding:20px
}
</style>
</head>

<body>

<header>
<strong>🍽️ R-Restaurant Al Halal</strong>

<nav>
<a href="#menu">Menu</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">

<h1>Bienvenue chez R-Restaurant Al Halal</h1>

<p>
Des plats savoureux, préparés avec soin
et dans le respect du halal.
</p>

<a class="btn" href="#menu">
Découvrir le menu
</a>

</section>

<section id="menu" class="section">

<h2>Notre menu</h2>

<div class="grid">

<div class="card">
<h3>🍗 Poulet grillé</h3>
<p>Poulet tendre, épices maison et accompagnement.</p>
<div class="price">3 500 FCFA</div>
</div>

<div class="card">
<h3>🍚 Riz au poulet</h3>
<p>Riz parfumé accompagné de poulet halal.</p>
<div class="price">3 000 FCFA</div>
</div>

<div class="card">
<h3>🥩 Viande grillée</h3>
<p>Viande savoureuse grillée à la perfection.</p>
<div class="price">4 000 FCFA</div>
</div>

<div class="card">
<h3>🥗 Salade fraîche</h3>
<p>Légumes frais et sauce maison.</p>
<div class="price">2 000 FCFA</div>
</div>

</div>

</section>

<section id="contact" class="section contact">

<h2>Commandez dès maintenant</h2>

<p>📞 Téléphone : votre numéro</p>

<p>📍 R-Restaurant Al Halal</p>

</section>

<footer>
© 2026 R-Restaurant Al Halal — Tous droits réservés.
</footer>

</body>
</html>
