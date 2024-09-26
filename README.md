# my-page-web<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loisirs & Apprentissage - Gagnez en Apprenant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #008080;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            margin: 20px;
            padding: 20px;
        }
        footer {
            background-color: #008080;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .affiliate-link {
            background-color: #f9f9f9;
            padding: 10px;
            border: 1px solid #ddd;
            margin: 20px 0;
        }
        .affiliate-link:hover {
            background-color: #e0ffff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenue sur ma page de Loisirs et Apprentissage</h1>
        <p>Découvrez des ressources et des produits qui peuvent enrichir votre vie tout en soutenant mon travail.</p>
    </header>

    <nav>
        <a href="#loisirs">Loisirs</a>
        <a href="#apprentissage">Apprentissage</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="loisirs">
        <h2>Mes Loisirs Favoris</h2>
        <p>Partagez mes passions pour le sport, la musique et la lecture. Voici quelques produits que je recommande, et en utilisant mes liens, vous pouvez soutenir mon travail sans frais supplémentaires.</p>
        
        <!-- Exemple de lien d'affiliation Amazon -->
        <div class="affiliate-link">
            <h3>Mes recommandations pour le sport</h3>
            <p>Je recommande cet équipement de randonnée disponible sur Amazon :</p>
            <a href="https://www.amazon.fr/dp/B07XYZ12345?tag=tonidaffilié" target="_blank">Voir l'article sur Amazon</a> <!-- Lien d'affiliation -->
        </div>

        <div class="affiliate-link">
            <h3>Apprendre la musique facilement</h3>
            <p>Pour apprendre à jouer du piano, j'utilise cette application de cours en ligne :</p>
            <a href="https://www.udemy.com/course/piano-for-beginners/?affcode=tonidaffilié" target="_blank">Cours de piano sur Udemy</a> <!-- Lien d'affiliation -->
        </div>
    </section>

    <section id="apprentissage">
        <h2>Apprentissage & Cours en ligne</h2>
        <p>Voici quelques plateformes d'apprentissage en ligne où vous pouvez suivre des cours pour améliorer vos compétences :</p>
        <ul>
            <li><a href="https://www.coursera.org?affcode=tonidaffilié" target="_blank">Cours sur Coursera</a></li> <!-- Lien d'affiliation -->
            <li><a href="https://www.udemy.com/?affcode=tonidaffilié" target="_blank">Cours sur Udemy</a></li> <!-- Lien d'affiliation -->
        </ul>
    </section>

    <section id="contact">
        <h2>Contact & Réseaux Sociaux</h2>
        <p>Envie de me contacter ou de me suivre ? Rejoignez-moi sur :</p>
        <ul>
            <li><a href="https://www.linkedin.com/">LinkedIn</a></li>
            <li><a href="https://www.twitter.com/">Twitter</a></li>
            <li><a href="https://www.instagram.com/">Instagram</a></li>
        </ul>
    </section>

    <footer>
        <p>© 2024 - Ma Page de Loisirs et Apprentissage</p>
    </footer>

</body>
</html>
