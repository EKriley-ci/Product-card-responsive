Frontend Mentor - Product Preview Card Component
Ceci est une solution au défi Product preview card component sur Frontend Mentor. Les défis Frontend Mentor vous aident à améliorer vos compétences en codage en réalisant des projets réalistes.

Aperçu
Le défi
Le défi consistait à créer une carte de prévisualisation de produit affichant des informations sur un parfum, avec des images adaptatives pour les différentes tailles d'écran.

Capture d'écran

Liens
URL de la solution

URL du site en ligne

Mon Processus
Construit avec
HTML5 sémantique

Propriétés personnalisées CSS

Flexbox

Media Queries

Ce que j'ai appris
Travailler sur ce projet m'a permis de :

Utiliser Flexbox pour créer une mise en page réactive et centrée.

Styliser des composants avec des propriétés CSS personnalisées.

Mettre en œuvre des media queries pour une meilleure adaptabilité des images et du contenu.

Voici un extrait de code dont je suis fier :

html

Copier
<picture>
    <source media="(max-width: 430px)" srcset="images/image-product-mobile.jpg">
    <source media="(min-width: 431px)" srcset="images/image-product-desktop.jpg">
    <img src="images/image-product-mobile.jpg" alt="" width="100%">
</picture>
css

Copier
button {
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    font-size: 1.3rem;
    font-weight: 700;
    color: white;
    outline: none;
    border: none;
    border-radius: 10px;
    background-color: hsl(158, 36%, 37%);
}
button:hover {
    background-color: hsl(158, 46%, 19%);
}
button:active {
    transform: scale(0.98);
}
Auteur
GitHub - @EKriley-ci

Frontend Mentor - @EKriley-ci

