girt# GameShop

GameShop est une page web de boutique de jeux vidéo. Elle présente une barre de navigation, une bannière d’accueil, des catégories, des promotions, des services et une section de contact.

## Lancer le projet

Le projet est statique : aucune installation ni compilation n’est nécessaire.

1. Ouvrir `index.html` dans un navigateur.
2. Une connexion Internet est nécessaire pour charger Bootstrap depuis jsDelivr ainsi que les images hébergées sur Unsplash.

## Fichiers du projet

- `index.html` : structure et contenu de la page.
- `style.css` : styles personnalisés, mise en page et animations.
- `gamestore-logo.png` : icône de la page.

## Changements apportés aux cartes de catégories

- Les cartes occupent toute la largeur de leur colonne avec `width: 100%;`, afin d’avoir une largeur uniforme.
- Elles utilisent une hauteur minimale de `170px` et Flexbox pour aligner leur contenu au centre.
- L’animation `Scrollct` déplace doucement chaque carte de gauche à droite sur 12 pixels au total, puis la ramène, avec une durée de 3 secondes et une transition `ease-in-out`.
- La propriété mal orthographiée `widht` a été corrigée en `width`, afin que le navigateur applique bien la règle de largeur.

## Technologies

- HTML5
- CSS3
- Bootstrap 5.3.8, chargé depuis un CDN
