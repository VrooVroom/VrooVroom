<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MusicRevolution - Révolutionnez votre musique</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>MusicRevolution</h1>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#instrumentales">Instrumentales</a></li>
                <li><a href="#soundkits">Sound Kits</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="accueil">
        <h2>Révolutionnez votre musique avec MusicRevolution</h2>
        <div class="hero-container">
            <div class="animated-image">
                <img src="kendrick_lamar_image1.gif" alt="Kendrick Lamar Image 1">
            </div>
            <div class="animated-image">
                <img src="kendrick_lamar_image2.gif" alt="Kendrick Lamar Image 2">
            </div>
            <div class="animated-image">
                <img src="kendrick_lamar_image3.gif" alt="Kendrick Lamar Image 3">
            </div>
        </div>
        <a href="#instrumentales" class="cta-button">Découvrir les instrumentales</a>
        <a href="#soundkits" class="cta-button">Explorer les sound kits</a>
    </section>
    <section id="instrumentales">
        <h2>Instrumentales</h2>
        <div class="product">
            <img src="instrumentale1.jpg" alt="Instrumentale 1">
            <h3>Nom de l'instrumentale 1</h3>
            <p>Description de l'instrumentale 1. Laissez-vous emporter par les mélodies captivantes et les rythmes novateurs.</p>
            <a href="#" class="cta-button">Acheter</a>
        </div>
        <div class="product">
            <img src="instrumentale2.jpg" alt="Instrumentale 2">
            <h3>Nom de l'instrumentale 2</h3>
            <p>Description de l'instrumentale 2. Plongez dans un univers sonore unique et laissez votre inspiration s'exprimer.</p>
            <a href="#" class="cta-button">Acheter</a>
        </div>
        <!-- Ajoutez d'autres instrumentales ici -->
    </section>
    <section id="soundkits">
        <h2>Sound Kits</h2>
        <div class="product">
            <img src="soundkit1.jpg" alt="Sound Kit 1">
            <h3>Nom du sound kit 1</h3>
            <p>Description du sound kit 1. Découvrez une collection de sons innovants pour créer des pistes uniques.</p>
            <a href="#" class="cta-button">Acheter</a>
        </div>
        <div class="product">
            <img src="soundkit2.jpg" alt="Sound Kit 2">
            <h3>Nom du sound kit 2</h3>
            <p>Description du sound kit 2. Expérimentez avec des sons révolutionnaires et repoussez les limites de votre musique.</p>
            <a href="#" class="cta-button">Acheter</a>
        </div>
        <!-- Ajoutez d'autres sound kits ici -->
    </section>
    <section id="contact">
        <h2>Contactez-nous</h2>
        <p>Pour toute question ou demande spécifique, veuillez remplir le formulaire ci-dessous :</p>
        <form action="envoyer_message.php" method="POST">
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 MusicRevolution. Tous droits réservés.</p>
    </footer>
</body>
</html>
