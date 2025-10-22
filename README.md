<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio de M.J</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- ====== SECTION D'ACCUEIL ====== -->
    <header id="index">
        <div class="overlay">
            <h1>Bienvenue sur mon Portfolio</h1>
            <p>Je suis <strong>M.J</strong> – Étudiant en Physique à l’USTM</p>
            <a href="#contact" class="btn">Me Contacter</a>
        </div>
    </header>

    <!-- ====== SECTION COMPÉTENCES ====== -->
    <section id="competences">
        <h2>Mes Compétences</h2>
        <ul>
            <li>HTML / CSS</li>
            <li>JavaScript (débutant)</li>
            <li>Programmation en Python</li>
            <li>Physique et Mathématiques</li>
        </ul>
    </section>

    <!-- ====== SECTION PROJETS ====== -->
    <section id="projets">
        <h2>Mes Projets</h2>
        <div class="projet">
            <h3>Calculatrice Scientifique</h3>
            <p>Création d’une calculatrice scientifique en JavaScript avec interface simple et responsive.</p>
        </div>

        <div class="projet">
            <h3>Mini IA en JavaScript</h3>
            <p>Développement d’une mini IA capable de répondre à des questions de base.</p>
        </div>
    </section>

    <!-- ====== SECTION EXPÉRIENCES ====== -->
    <section id="experiences">
        <h2>Mes Expériences</h2>
        <p>Étudiant à l’Université des Sciences et Techniques de Masuku (USTM).</p>
        <p>Participation à divers projets d’apprentissage en programmation et physique appliquée.</p>
    </section>

    <!-- ====== SECTION À PROPOS ====== -->
    <section id="apropos">
        <h2>À propos</h2>
        <p>Je suis passionné par la science, la technologie et le développement web.  
           J’aime apprendre et créer des projets utiles pour progresser dans mes études et mes compétences techniques.</p>
    </section>

    <!-- ====== SECTION CONTACT ====== -->
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="nom">Nom :</label>
            <input type="text" id="nom" placeholder="Votre nom">

            <label for="email">Email :</label>
            <input type="email" id="email" placeholder="Votre adresse email">

            <label for="message">Message :</label>
            <textarea id="message" rows="5" placeholder="Votre message..."></textarea>

            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>© 2025 M.J | Portfolio USTM</p>
    </footer>

</body>
</html>