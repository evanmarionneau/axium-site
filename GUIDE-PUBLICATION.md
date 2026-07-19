# Publier le site ELAVERIS sur GitHub Pages

## Fichiers à mettre dans le dépôt

Dans le dépôt GitHub actuel `axium-site`, remplacez ou ajoutez à la racine :

- `index.html`
- `favicon.svg`
- `logo-elaveris.svg`
- `logo-elaveris.png`
- `og-elaveris.png`

Le fichier `og-elaveris.svg` est la version modifiable du visuel de partage. Il peut aussi être conservé dans le dépôt, mais le site utilise sa version PNG.

## Mise en ligne

1. Ouvrez le dépôt `axium-site` sur GitHub.
2. Utilisez **Add file**, puis **Upload files**.
3. Sélectionnez les fichiers extraits du ZIP — pas le ZIP lui-même.
4. Validez avec **Commit changes** sur la branche `main`.
5. Dans **Settings > Pages**, vérifiez que la publication utilise **Deploy from a branch**, branche `main`, dossier `/ (root)`.
6. Attendez quelques minutes, puis ouvrez `https://evanmarionneau.github.io/axium-site/`.

## Si l’adresse change plus tard

Si le dépôt est renommé ou si un nom de domaine ELAVERIS est acheté, mettez à jour dans `index.html` les valeurs `og:url`, `og:image` et `canonical` avec la nouvelle adresse.

## Avant le lancement commercial

Complétez les informations juridiques, les conditions d’intervention, la politique de confidentialité si des données sont collectées, ainsi que l’adresse e-mail professionnelle lorsqu’elle sera créée.
