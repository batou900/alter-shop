# Alter - boutique (shop.alteralteralter.com)

Page unique : grille de pièces, fenêtre de détail (lightbox), contact.

- `index.html` : toute la page. Les pièces sont dans le tableau `items` du script.
- Les images sont actuellement intégrées dans le fichier (base64), ce qui le rend lourd (~4 Mo).
  À terme : les sortir dans un dossier `images/` pour alléger la page et faciliter les mises à jour.

Hébergement : Netlify, projet `altershop` (le `netlify.toml` à la racine du dépôt publie ce dossier, sans build).
