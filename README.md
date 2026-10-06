# Marrakech, 12 au 15 octobre 2026

Carnet de voyage en mode application, protégé par mot de passe.

- `index.html` : l'application complète, autonome. Son contenu est chiffré (AES-256) : sans le mot de passe, le code source ne révèle ni les adresses, ni les photos, ni le programme.
- `apple-touch-icon.png`, `favicon.ico`, `favicon-32.png`, `icon-192.png`, `icon-512.png`, `manifest.webmanifest` : icônes de l'app (onglet du navigateur et écran d'accueil de l'iPhone).
- Les photos d'origine ne sont volontairement pas dans ce dépôt : elles restent dans `marrakech_images.zip`, à garder en local.

## Publier avec GitHub Pages

Dépôt : https://github.com/s-dsf/marrakech-2026

```bash
git init
git add .
git commit -m "Carnet de voyage Marrakech"
git branch -M main
git remote add origin https://github.com/s-dsf/marrakech-2026.git
git push -u origin main
```

Puis sur GitHub : Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
L'app sera à : https://s-dsf.github.io/marrakech-2026/

## Ajouter l'app à l'écran d'accueil de l'iPhone

Ouvre l'adresse ci-dessus dans Safari, touche le bouton Partager, puis « Sur l'écran d'accueil ».
