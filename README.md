<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Trans Coursier – Livraison, Transport & Déménagement</title>
  <meta name="description" content="Trans Coursier : livraison express, transport de marchandises et déménagement pour particuliers & entreprises – Évreux, Normandie, Île-de-France & Europe." />
  <style>
    :root{
      --tc-navy:#002273;
      --tc-red:#BF2E0B;
      --radius:18px;
      --shadow:0 10px 30px rgba(0,0,0,.08);
    }
    body{margin:0;font-family:"Helvetica Neue", Helvetica, Arial, sans-serif;background:#f7f8fc;color:#0b1220}
    a{color:inherit;text-decoration:none}
    .container{width:min(1160px, 92%);margin:auto}
    header{background:#fff;border-bottom:1px solid #e9eef5;position:sticky;top:0;z-index:10}
    .nav{display:flex;justify-content:space-between;align-items:center;padding:14px 0}
    .brand strong{color:var(--tc-navy);font-weight:800}
    nav ul{display:flex;list-style:none;gap:24px;margin:0;padding:0}
    nav a{font-weight:600;opacity:.85}
    .cta{background:var(--tc-red);color:#fff;padding:10px 18px;border-radius:999px;font-weight:700;box-shadow:var(--shadow)}
    .hero{padding:68px 0;display:grid;gap:40px;grid-template-columns:1fr 1fr;align-items:center}
    h1{color:var(--tc-navy);font-size:clamp(32px,5vw,52px);margin:0 0 14px}
    .lead{font-size:18px;opacity:.85}
    section{padding:64px 0}
    h2{color:var(--tc-navy)}
    .grid{display:grid;gap:22px}
    .cols-3{grid-template-columns:repeat(3,1fr)}
    .cols-2{grid-template-columns:repeat(2,1fr)}
    .card{background:#fff;border-radius:var(--radius);padding:24px;box-shadow:var(--shadow)}
    .muted{opacity:.72}
    .check{color:var(--tc-navy);font-weight:700}
    footer{background:#0a1740;color:#c9d4ff;padding:36px 0}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand"><strong>TRANS COURSIER</strong></div>
      <nav>
        <ul>
          <li><a href="#services">Prestations</a></li>
          <li><a href="#pourquoi">Pourquoi nous</a></li>
          <li><a href="#avis">Avis</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
      <a class="cta" href="#contact">Demander un devis</a>
    </div>
  </header>

  <section class="hero container">
    <div>
      <h1>Livraison, Transport & Déménagement en toute confiance</h1>
      <p class="lead">Basés à Évreux, nous intervenons en Normandie, Île‑de‑France et en Europe. Rapides, fiables et flexibles, nous prenons en charge vos biens avec soin.</p>
      <a class="cta" href="#contact">Obtenir un devis gratuit</a>
    </div>
    <div>
      <!-- Ici on peut insérer un visuel inspiré de la charte graphique -->
    </div>
  </section>

  <section id="services" class="container">
    <h2>Nos prestations</h2>
    <div class="grid cols-3">
      <div class="card"><h3>Livraison express & régulière</h3><p class="muted">Courses dédiées, tournées planifiées, enlèvements et livraisons dans la journée.</p></div>
      <div class="card"><h3>Transport de marchandises</h3><p class="muted">Colis volumineux, palettes et matériel. Véhicules adaptés et suivi.</p></div>
      <div class="card"><h3>Déménagement particulier & pro</h3><p class="muted">Prise en charge complète ou à la carte : emballage, manutention, montage.</p></div>
    </div>
  </section>

  <section id="pourquoi" class="container">
    <h2>Pourquoi choisir Trans Coursier ?</h2>
    <div class="grid cols-2">
      <ul class="muted" style="line-height:1.9">
        <li><span class="check">✔</span> <strong>Tarifs 100% transparents</strong> : devis clairs et rapides, sans mauvaise surprise.</li>
        <li><span class="check">✔</span> <strong>Réactivité 7j/7</strong> : interventions week‑end et soirées possibles.</li>
        <li><span class="check">✔</span> <strong>Suivi digital & sérénité</strong> : notifications par SMS/WhatsApp, confirmation de livraison avec photo.</li>
        <li><span class="check">✔</span> <strong>Respect de l’environnement</strong> : trajets optimisés et véhicules propres.</li>
        <li><span class="check">✔</span> <strong>Service humain et local</strong> : un interlocuteur unique basé à Évreux.</li>
        <li><span class="check">✔</span> <strong>Solutions sur‑mesure</strong> : colis fragiles, palettes, déménagement complet.</li>
        <li><span class="check">✔</span> <strong>Garantie de ponctualité et sécurité</strong> : assurance incluse et engagement sur délais.</li>
      </ul>
    </div>
  </section>

  <section id="avis" class="container">
    <h2>Ils nous font confiance</h2>
    <div class="grid cols-3">
      <div class="card"><p>“Enlèvement le matin, livré à Paris l’après‑midi. Super réactifs !”</p><span class="muted">— Claire, PME retail</span></div>
      <div class="card"><p>“Déménagement soigné et ponctuel. Équipe arrangeante, je recommande.”</p><span class="muted">— Jonathan, particulier</span></div>
      <div class="card"><p>“Tarifs clairs, chauffeur pro. Nous referons appel à eux.”</p><span class="muted">— Camille, agence événementielle</span></div>
    </div>
  </section>

  <section id="contact" class="container">
    <h2>Contact & devis</h2>
    <p class="muted">Parlez‑nous de votre besoin. Nous vous recontactons rapidement.</p>
    <form>
      <input required placeholder="Nom Prénom" />
      <input required type="tel" placeholder="Téléphone" />
      <input required type="email" placeholder="Email" />
      <textarea placeholder="Votre message"></textarea>
      <button class="cta" type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <div class="container">
      <p>© <span id="year"></span> Trans Coursier — Livraison • Transport • Déménagement</p>
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
