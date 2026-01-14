<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Jules Fitness - Coaching & Marque Sportive</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
*{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth;}
body{font-family:Arial,sans-serif;background:#111;color:#fff;}
nav{position:fixed;width:100%;top:0;left:0;background:rgba(0,0,0,0.95);display:flex;justify-content:space-between;align-items:center;padding:15px 50px;z-index:1000;}
nav h1{color:#f44336;font-size:1.7em;}
nav ul{list-style:none;display:flex;gap:20px;}
nav ul li a{color:#fff;text-decoration:none;font-weight:bold;transition:0.3s;}
nav ul li a:hover{color:#f44336;}
header{background:url('https://images.unsplash.com/photo-1599058917212-d750089bc07d?fit=crop&w=1600&q=80')center/cover no-repeat;height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:0 20px;}
header h2{font-size:3em;color:#f44336;margin-bottom:10px;text-shadow:2px 2px 8px #000;}
header p{font-size:1.3em;margin-bottom:20px;text-shadow:1px 1px 5px #000;}
header .btn{padding:15px 30px;background:#f44336;border-radius:30px;text-decoration:none;color:#fff;transition:0.3s;}
header .btn:hover{background:#d32f2f;}
section{padding:80px 20px;max-width:1100px;margin:auto;}
section h2{text-align:center;color:#f44336;margin-bottom:40px;}
.services,.pricing{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
.card{background:#222;padding:25px;border-radius:10px;text-align:center;transition:0.3s;overflow:hidden;position:relative;}
.card img{width:100%;height:180px;object-fit:cover;border-radius:10px 10px 0 0;margin-bottom:15px;}
.card:hover{transform:scale(1.05);box-shadow:0 0 15px #f44336;}
.card h3{color:#f44336;margin-bottom:10px;}
.card p{margin-bottom:15px;}
.btn{display:inline-block;margin-top:10px;padding:12px 25px;background:#f44336;color:#fff;text-decoration:none;border-radius:30px;transition:0.3s;}
.btn:hover{background:#d32f2f;}
.vitastong{background:linear-gradient(135deg,#1b1b1b,#000);border:2px solid #f44336;border-radius:15px;padding:40px;text-align:center;margin-bottom:40px;}
.vitastong .code{font-size:1.8em;font-weight:bold;color:#f44336;margin:20px 0;}
.brand{background:linear-gradient(135deg,#111,#000);border:2px solid #00bcd4;border-radius:15px;padding:40px;text-align:center;margin-bottom:40px;}
#contact p a{color:#f44336;text-decoration:none;}
footer{background:#000;text-align:center;padding:20px;font-size:0.9em;}
@media(max-width:768px){nav{flex-direction:column;gap:10px;padding:15px 20px;}header h2{font-size:2.2em;}header p{font-size:1em;}}
</style>
</head>
<body>

<nav>
<h1>Jules Fitness</h1>
<ul>
<li><a href="#about">À propos</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#vitastong">VitaStrong</a></li>
<li><a href="#brand">Ma marque</a></li>
<li><a href="#pricing">Tarifs</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<header>
<h2>Jules Fitness</h2>
<p>Coaching • Performance • Transformation physique</p>
<a href="#contact" class="btn">Réserver une séance</a>
</header>

<section id="about">
<h2>À propos</h2>
<p>Coach sportif certifié, j’accompagne hommes et femmes dans leurs objectifs physiques : perte de poids, prise de muscle, préparation physique et amélioration des performances, en présentiel ou en visio.</p>
</section>

<section id="services">
<h2>Mes services</h2>
<div class="services">
<div class="card">
<img src="https://images.unsplash.com/photo-1599058917212-d750089bc07d?fit=crop&w=600&q=80" alt="Coaching individuel">
<h3>1 séance individuelle</h3>
<p>Coaching personnalisé sur mesure adapté à ton niveau et à tes objectifs.</p>
</div>
<div class="card">
<img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1?fit=crop&w=600&q=80" alt="Coaching visio">
<h3>Vidéo coaching</h3>
<p>Accompagnement à distance avec suivi personnalisé.</p>
</div>
<div class="card">
<img src="https://images.unsplash.com/photo-1571019613575-2c92007f9c41?fit=crop&w=600&q=80" alt="Plan entrainement">
<h3>Programmation d'entraînement</h3>
<p>Plans d’entraînement personnalisés pour progresser chez soi ou en salle.</p>
</div>
</div>
</section>

<section id="vitastong">
<h2>VitaStrong – Nutrition & Compléments</h2>
<div class="vitastong">
<p>Je suis ambassadeur officiel de la marque <strong>VitaStrong</strong>, spécialisée dans les compléments nutritionnels pour la performance et la récupération.</p>
<p>🎁 Profite de <strong>-20%</strong> avec mon code promo :</p>
<div class="code">JULES06</div>
<a href="https://vitastong.com" target="_blank" class="btn">Découvrir VitaStrong</a>
</div>
</section>

<section id="brand">
<h2>Ma marque de vêtements</h2>
<div class="brand">
<p>Dans le futur, je lancerai ma propre <strong>marque de vêtements de sport</strong>, pensée pour le confort, la performance et le style.</p>
<p>Reste connecté pour découvrir des collections exclusives et des collaborations spéciales.</p>
<a href="#contact" class="btn" style="background:#00bcd4;">Être informé du lancement</a>
</div>
</section>

<section id="pricing">
<h2>Tarifs & Paiement</h2>
<div class="pricing">
<div class="card">
<h3>1 séance individuelle</h3>
<p>20€</p>
<a href="#" class="btn">Paiement à venir</a>
</div>
<div class="card">
<h3>Vidéo coaching</h3>
<p>30€/heure</p>
<a href="#" class="btn">Paiement à venir</a>
</div>
<div class="card">
<h3>Programmation d'entraînement</h3>
<p>40€/mois</p>
<a href="#" class="btn">Paiement à venir</a>
</div>
</div>
</section>

<section id="contact">
<h2>Contact</h2>
<p>Téléphone : <a href="tel:+33768386811">07 68 38 68 11</a></p>
<p>Email : <a href="mailto:julessimula56@gmail.com">julessimula56@gmail.com</a></p>
<p>Instagram : @coachsportif</p>
<a href="mailto:julessimula56@gmail.com" class="btn">Me contacter</a>
</section>

<footer>
© 2026 - Jules Fitness | Coaching & Préparation Physique
</footer>

</body>
</html>
