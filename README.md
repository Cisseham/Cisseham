<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Web Personnelle</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        section {
            background-color: white;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #007acc;
        }
        .social-links a {
            margin-right: 10px;
            text-decoration: none;
            color: #007acc;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        .contact-form button {
            background-color: #007acc;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page personnelle</h1>
    </header>

    <div class="container">
        <!-- Section Présentation -->
        <section>
            <h2>Présentation</h2>
            <p>Bonjour ! Je m'appelle [Votre Nom]. Je suis passionné(e) par le développement web et j'aime explorer de nouvelles technologies.</p>
        </section>

        <!-- Section Expérience professionnelle -->
        <section>
            <h2>Expérience professionnelle</h2>
            <p>Actuellement, je travaille comme développeur web avec une expérience dans diverses technologies front-end et back-end.</p>
        </section>

        <!-- Section Centres d'intérêt -->
        <section>
            <h2>Centres d'intérêt</h2>
            <p>En dehors du travail, j'adore la photographie, les voyages et la musique.</p>
        </section>

        <!-- Liens vers les réseaux sociaux -->
        <section class="social-links">
            <h2>Retrouvez-moi sur</h2>
            <a href="https://github.com/" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        </section>

        <!-- Formulaire de contact -->
        <section>
            <h2>Contactez-moi</h2>
            <form class="contact-form">
                <input type="text" placeholder="Votre nom" required>
                <input type="email" placeholder="Votre adresse e-mail" required>
                <textarea placeholder="Votre message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </section>
    </div>
</body>
</html>
