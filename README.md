# IA PRATIQUE — Page de vente

Page de vente de l'ebook **IA PRATIQUE** de Gaston N3 (HTML/CSS/JS, un seul fichier, sans dépendance).

## Mettre en ligne avec GitHub Pages
1. Crée un dépôt GitHub et envoie `index.html` (et `README.md`).
2. Dépôt > **Settings** > **Pages** > Source : **Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Après quelques minutes, ta page est en ligne à l'adresse `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Fichiers
- `index.html` : la version à publier (aucun chiffre ni avis d'exemple).
- `apercu-demo.html` : aperçu du design avec chiffres et avis d'exemple, à garder pour toi, ne pas publier.

## Ajouter tes vrais chiffres (dans `index.html`, cherche `var OFFER=`)
```js
var OFFER={sales:42, reviews:12, deadline:"2026-10-31T23:59:59"};
```
- `sales` et `reviews` : tes vrais nombres (affichés seulement si tu les renseignes).
- `deadline` : la vraie date de fin de l'offre (le chrono s'affiche seulement avec une date).

## Afficher le carrousel de témoignages (dans `index.html`)
Cherche `AFFICHER_TEMOIGNAGES=false` et passe-le à `true`, seulement si ce sont de vrais avis approuvés par les clients.

Contact WhatsApp : 06 862 17 44 (modifiable dans la variable `link`).
