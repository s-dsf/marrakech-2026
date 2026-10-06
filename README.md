# Marrakech, 12 au 15 octobre 2026

Carnet de voyage en mode application, protégé par mot de passe.

- `index.html` : l'application complète, autonome. Son contenu est chiffré (AES-256) : sans le mot de passe, le code source ne révèle ni les adresses, ni les photos, ni le programme.
- Les photos d'origine ne sont volontairement pas dans ce dépôt : elles restent dans `marrakech_images.zip`, à garder en local.

## Publier avec GitHub Pages

```bash
git init
git add .
git commit -m "Carnet de voyage Marrakech"
git branch -M main
git remote add origin https://github.com/<ton-compte>/<ton-depot>.git
git push -u origin main
```

Puis sur GitHub : Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.

Pour changer le mot de passe ou modifier le contenu, il faut régénérer `index.html` : demande-le à Claude.
