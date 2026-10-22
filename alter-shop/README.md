# Alter - boutique (shop.alteralteralter.com)

Page unique : grille de pièces et fenêtre de détail (lightbox).

- `index.html` : toute la page. Les pièces sont dans le tableau `items` du script.
- `images/` : toutes les photos (et le logo). Chaque pièce liste ses photos dans `images:[...]`.

Ajouter une photo à une pièce :
1. Sur GitHub, ouvrir `alter-shop/images`, puis « Add file » > « Upload files » (JPG, 2000 px max sur le grand côté).
2. Dans `index.html`, trouver la pièce (ex. `name:"Bank DayBed"`) et ajouter `,"images/nom-du-fichier.jpg"` avant le `]` de sa ligne `images:`.
   La première photo de la liste sert de couverture dans la grille.
3. « Commit changes » : chaque commit sur `main` déclenche une mise en ligne Netlify (et consomme des crédits) — tout faire en un seul commit si possible.

Hébergement : Netlify, projet `altershop` (le `netlify.toml` à la racine du dépôt publie ce dossier, sans build).

- `legal.html` : mentions légales + politique de confidentialité (obligatoires en Belgique / UE).
  Les infos de l’ASBL (BCE, TVA, siège) ne sont que là ; le bas de `index.html` y renvoie.
- `fonts/` : police Inter hébergée ici plutôt que chez Google (RGPD : aucune donnée de visiteur envoyée à un tiers).
