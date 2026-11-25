# CLAUDE.md

## Le produit
Jeu de conquête pour téléphone, où le joueur étend son territoire et affronte d'autres joueurs.
Il s'adresse aux joueurs mobiles de 10 à 35 ans, pour s'amuser en quelques minutes, n'importe où.

## Ton des textes
- Tutoie toujours le joueur : « tu », « ton », « tes ». Jamais « vous ».
- Écris des phrases courtes : 15 mots maximum.
- N'utilise aucun jargon ni mot technique : explique avec des mots du quotidien.
- Écris tous les textes visibles en français.

## Règles techniques
- Le jeu tient dans une seule page : `index.html` à la racine du dépôt.
- Le style va dans `index.html` ou dans un seul fichier `style.css`. Pas d'autre fichier de style.
- La page doit être lisible sur un écran d'iPhone : balise `viewport` présente, texte de 16 px minimum, pas de défilement horizontal.
- Aucun service extérieur : pas de CDN, pas de police en ligne, pas de script ni d'image venant d'une autre adresse.
- La page doit s'ouvrir et marcher en double-cliquant sur `index.html`, sans serveur ni installation.

## Avant chaque commit
- Ouvre `index.html` à une largeur de 390 px (taille d'un iPhone) : tout le texte se lit et aucun bouton n'est coupé.
- Cherche `http://` et `https://` dans les fichiers : aucun lien vers un service extérieur ne doit apparaître.
- Écris le message de commit en français, à l'indicatif présent, en une phrase qui dit ce qui change (exemple : « Ajoute le bouton Rejouer »).
