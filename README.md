<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Universal Tech</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f7fa;
      color: #333;
      text-align: center;
    }
    header {
      padding: 20px;
      background: #0a3d62;
      color: white;
    }
    header img {
      width: 100px;
      margin-bottom: 10px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-style: italic;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .service {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #0a3d62;
      color: white;
      padding: 15px;
      margin-top: 40px;
    }
    a {
      color: #0a3d62;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Logo The Universal Tech">
    <h1>The Universal Tech</h1>
    <p>La technologie sans frontières</p>
  </header>

  <section>
    <h2>À propos</h2>
    <p>
      The Universal Tech est un projet dédié à l’informatique et à l’innovation. 
      Notre objectif est de créer des solutions accessibles à tous et d’accompagner 
      le monde vers une transformation numérique durable.
    </p>
  </section>

  <section>
    <h2>Nos services</h2>
    <div class="services">
      <div class="service">
        <h3>💻 Développement</h3>
        <p>Création de sites web modernes et d’applications sur mesure.</p>
      </div>
      <div class="service">
        <h3>🔧 Assistance</h3>
        <p>Support technique et formation pour vos besoins numériques.</p>
      </div>
      <div class="service">
        <h3>🚀 Innovation</h3>
        <p>Des solutions technologiques pensées pour l’avenir.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Email : <a href="mailto:contact@theuniversaltech.com">contact@theuniversaltech.com</a></p>
    <p>Suivez-nous sur :
      <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">LinkedIn</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 The Universal Tech. Tous droits réservés.</p>
  </footer>

</body>
</html>
