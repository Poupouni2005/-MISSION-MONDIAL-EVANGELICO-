<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <title>MMEFJA – Mission Mondial Évangélico</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Mission Mondial Évangélico Fondation Jockeirocher de Akouédo Attié - Église à Abatta, Cocody" />
  <style>
    :root {
      --bg: #1F3B57;
      --accent: #2EC4B6;
      --highlight: #FF6B6B;
      --text-light: #F7F9FC;
      --radius: 14px;
      --shadow: 0 20px 40px -10px rgba(31,59,87,0.4);
      font-family: "Inter", system-ui,-apple-system,BlinkMacSystemFont,sans-serif;
    }
    * { box-sizing:border-box; }
    body {
      margin:0;
      background: linear-gradient(135deg, var(--bg) 0%, #0f2d44 75%);
      color: var(--text-light);
      line-height:1.5;
    }
    a { color: inherit; text-decoration:none; }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 1rem;
    }
    header {
      display:flex;
      justify-content:space-between;
      align-items:center;
      flex-wrap:wrap;
      padding:1rem 0;
    }
    .logo {
      font-size:1.5rem;
      font-weight:700;
    }
    nav {
      display:flex;
      gap:1rem;
      flex-wrap: wrap;
    }
    nav a {
      font-weight:500;
      padding: .5rem;
      border-radius:6px;
    }
    nav a:hover {
      background: rgba(255,255,255,0.1);
    }
    .hero {
      display:flex;
      flex-wrap:wrap;
      gap:2rem;
      align-items:center;
      margin:2rem 0;
    }
    .hero h1 {
      font-size:2.4rem;
    }
    .btn-primary {
      background: var(--highlight);
      padding: .75rem 1.5rem;
      border-radius:999px;
      color:white;
      font-weight:bold;
      display:inline-block;
      margin-top:1rem;
    }
    .section-title {
      margin-top:3rem;
      margin-bottom:1rem;
      font-size:1.8rem;
      font-weight:bold;
      border-left:4px solid var(--accent);
      padding-left:.75rem;
    }
    .cards {
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap:1.5rem;
    }
    .card {
      background: rgba(255,255,255,0.05);
      padding:1rem;
      border-radius:var(--radius);
    }
    iframe {
      width:100%;
      height:300px;
      border:0;
      border-radius:var(--radius);
    }
    footer {
      text-align:center;
      margin-top:4rem;
      padding:2rem 0;
      font-size:.9rem;
      border-top:1px solid rgba(255,255,255,0.2);
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">MMEFJA</div>
      <nav>
        <a href="#accueil">Accueil</a>
        <a href="#apropos">À propos</a>
        <a href="#sermons">Sermons</a>
        <a href="#evenements">Événements</a>
        <a href="#don">Don</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero" id="accueil">
      <div>
        <h1>Mission Mondial Évangélico Fondation Jockeirocher de Akouédo Attié</h1>
        <p>Nous sommes une église pentecôtiste située à Abatta, Cocody, non loin du Carrefour Drogba. Nous travaillons avec le Saint-Esprit pour impacter des vies.</p>
        <a href="#evenements" class="btn-primary">Rejoindre un culte</a>
      </div>
    </section>

    <div class="section-title" id="apropos">À propos</div>
    <div class="cards">
      <div class="card">
        <h3>Notre foi</h3>
        <p>Nous sommes des pentecôtistes convaincus, guidés par le Saint-Esprit. Nous croyons en la puissance de Dieu pour transformer les vies.</p>
      </div>
      <div class="card">
        <h3>Nos responsables</h3>
        <p><strong>Missionnaire :</strong> Emilienne</p>
        <p><strong>Grand Missionnaire :</strong> JOCKEIRROCHER</p>
        <p>Ils dirigent l'église avec passion, prière et dévouement pour le Royaume de Dieu.</p>
      </div>
    </div>

    <div class="section-title" id="sermons">Sermons</div>
    <div class="cards">
      <div class="card">
        <h3>Espoir renouvelé</h3>
        <p>Un message puissant pour raviver la foi et l'espérance en Christ.</p>
      </div>
      <div class="card">
        <h3>Vie en abondance</h3>
        <p>Découvrez la vie que Dieu veut pour vous, riche en paix et en bénédictions.</p>
      </div>
    </div>

    <div class="section-title" id="evenements">Événements</div>
    <div class="cards">
      <div class="card">
        <h3>Culte du dimanche</h3>
        <p><strong>Horaire :</strong> Tous les dimanches de 9h à 11h</p>
        <p>Un temps fort de louange, d’enseignement et de prière dans la présence du Saint-Esprit.</p>
      </div>
    </div>

    <div class="section-title" id="don">Soutenir la mission</div>
    <div class="cards">
      <div class="card">
        <h3>Faire un don</h3>
        <p>Soutenez notre mission d’évangélisation en participant par vos dons. Chaque contribution compte !</p>
      </div>
    </div>

    <div class="section-title" id="contact">Contact & Localisation</div>
    <div class="cards">
      <div class="card">
        <h3>Coordonnées</h3>
        <p><strong>Adresse :</strong> Abatta, Cocody, non loin du Carrefour Drogba</p>
        <p><strong>Téléphone :</strong> 0708983793</p>
      </div>
      <div class="card">
        <h3>Nous localiser</h3>
        <iframe src="https://www.google.com/maps?q=Carrefour+Drogba+Cocody+Abatta&output=embed"></iframe>
      </div>
    </div>

    <footer>
      &copy; 2025 MMEFJA – Mission Mondial Évangélico Fondation Jockeirocher de Akouédo Attié. Tous droits réservés.
    </footer>
  </div>
</body>
</html>
