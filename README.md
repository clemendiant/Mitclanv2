<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mictlan - Site officiel</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0F1923;
            color: #E0E0E0;
        }
        header {
            background-color: #FF4655;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }
        nav {
            background-color: #1F2326;
            display: flex;
            justify-content: center;
            padding: 1rem 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        nav a {
            color: #E0E0E0;
            text-decoration: none;
            margin: 0 1.5rem;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FF4655;
        }
        main {
            padding: 3rem;
            background-image: url('background.jpg');
            background-size: cover;
            background-attachment: fixed;
            background-blend-mode: overlay;
            background-color: rgba(15, 25, 35, 0.95);
        }
        section {
            margin-bottom: 3rem;
        }
        section h2 {
            font-size: 2.5rem;
            color: #FF4655;
            margin-bottom: 1rem;
        }
        .download-button {
            display: inline-block;
            background-color: #FF4655;
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .download-button:hover {
            background-color: #D43A4A;
        }
        footer {
            background-color: #1F2326;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 3rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mictlan</h1>
        <p>Plongez dans un univers mythologique intense</p>
    </header>
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#createurs">Créateurs</a>
        <a href="#projet">Le Projet</a>
    </nav>
    <main>
        <section id="accueil">
            <h2>Bienvenue sur Mictlan</h2>
            <p>Découvrez un rogue-like captivant inspiré des mythes aztèques. Préparez-vous à un défi unique où chaque mort n'est qu'un nouveau départ.</p>
            <a href="#" class="download-button">Téléchargez le jeu</a>
        </section>

        <section id="createurs">
            <h2>À propos des créateurs</h2>
            <p>Mictlan est développé par <strong>Battalion</strong>, une équipe passionnée qui cherche à révolutionner les rogue-like avec des concepts innovants et un gameplay immersif.</p>
        </section>

        <section id="projet">
            <h2>Présentation du projet</h2>
            <p>Dans Mictlan, incarnez un guerrier aztèque prisonnier d'un labyrinthe divin. Combattez des ennemis impitoyables, bravez la colère des dieux et révélez les secrets de Teotocan dans une quête de vengeance épique.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Battalion - Tous droits réservés</p>
    </footer>
</body>
</html>
