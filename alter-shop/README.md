# Alter - boutique (shop.alteralteralter.com)

Page unique : grille de pièces, fenêtre de détail (lightbox), contact.

- `index.html` : toute la page. Les pièces sont dans le tableau `items` du script.
- Les images sont actuellement intégrées dans le fichier (base64), ce qui le rend lourd (~4 Mo).
  À terme : les sortir dans un dossier `images/` pour alléger la page et faciliter les mises à jour.

Hébergement : Netlify, projet `altershop` (le `netlify.toml` à la racine du dépôt publie ce dossier, sans build).

- `legal.html` : mentions légales + politique de confidentialité (obligatoires en Belgique / UE).
  Les champs entre crochets (forme juridique, n° BCE, TVA, responsable) sont aussi dans le bas de `index.html`.
- `fonts/` : police Inter hébergée ici plutôt que chez Google (RGPD : aucune donnée de visiteur envoyée à un tiers).
