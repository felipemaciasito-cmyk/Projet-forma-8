# CLAUDE.md

## Le produit

Ce produit est un jeu de conquête pour téléphone, où le joueur agrandit son territoire en battant ses adversaires.
Il s'adresse aux joueurs de jeux mobiles de 10 à 35 ans, pour des parties courtes et faciles à prendre en main.

## Ton des textes

- Tutoie toujours le joueur (« tu », « ton », « ta »), jamais « vous ».
- Écris des phrases courtes : 15 mots maximum par phrase.
- N'utilise aucun jargon : pas de terme technique ni de mot anglais quand un mot français simple existe.
- Écris tous les textes affichés au joueur en français.

## Règles techniques

- Le jeu tient dans une seule page : `index.html` à la racine du dépôt.
- Si besoin, ajoute une seule feuille de style : `style.css`, à côté de `index.html`.
- Mets la balise `<meta name="viewport" content="width=device-width, initial-scale=1">` dans `index.html`.
- La page doit rester lisible sur un écran d'iPhone de 375 px de large, sans défilement horizontal.
- Utilise une taille de texte d'au moins 16 px et des boutons d'au moins 44 px de haut.
- N'utilise aucun service extérieur : pas de CDN, pas de police en ligne, pas d'API, pas de statistiques.
- N'ajoute aucun fichier à charger depuis internet : tout le code est dans le dépôt.

## Avant chaque commit

- Ouvre `index.html` dans un navigateur réglé sur la taille d'un iPhone (375 px de large).
- Vérifie que tous les textes se lisent et que rien ne dépasse de l'écran.
- Vérifie que `index.html` ne contient aucun lien `http://` ni `https://` vers l'extérieur.
- Écris le message de commit en français, en une phrase qui dit ce qui change.
- Commence le message par un verbe à l'infinitif, par exemple « Ajouter le bouton Jouer ».
