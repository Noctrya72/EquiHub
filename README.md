# Site de présentation — EquiHub

Site statique en HTML / CSS / JavaScript prévu pour être publié sur GitHub Pages.

## Structure

```text
EcurieApp-Download/
├── index.html
├── style.css
├── script.js
└── downloads/
    └── EcurieApp.apk
```

## Installer l'APK

Place ton APK dans :

`downloads/EcurieApp.apk`

Le bouton de téléchargement de `index.html` pointe déjà vers ce chemin.

## Ajouter les vraies captures d'écran

Dans `index.html`, la section `#captures` contient trois emplacements prévus pour les captures.

Tu peux ensuite remplacer chaque bloc `.screenshot-placeholder` par une vraie balise `<img>`.

## Publication GitHub Pages

1. Crée un dépôt public dédié à la distribution.
2. Mets `index.html`, `style.css`, `script.js` et le dossier `downloads`.
3. Dans GitHub : Settings → Pages.
4. Choisis la branche `main` et le dossier `/root`.
5. GitHub Pages donnera l'adresse du site.
