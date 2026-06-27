# FripIA PWA

Version installable de FripIA pour iPhone et navigateur mobile.

## Tester en local

Le dossier doit être servi par un petit serveur local, pas ouvert directement en fichier.

```bash
python -m http.server 8787
```

Puis ouvrir :

```text
http://127.0.0.1:8787/
```

## Installer sur iPhone

Pour une vraie installation sur l'écran d'accueil, publie d'abord le dossier sur un hébergement HTTPS comme GitHub Pages.

Ensuite sur iPhone :

1. Ouvrir l'URL dans Safari.
2. Toucher le bouton Partager.
3. Choisir `Sur l'écran d'accueil`.
4. Valider le nom `FripIA`.

L'app s'ouvrira ensuite en plein écran avec son icône.

## Fichiers PWA

- `index.html` : application FripIA.
- `manifest.webmanifest` : nom, icônes, couleur et mode standalone.
- `sw.js` : cache de base pour l'app shell.
- `icons/apple-touch-icon.png` : icône iPhone.
- `icons/icon-192.png` et `icons/icon-512.png` : icônes PWA.

## GitHub Pages

Copie le contenu de ce dossier à la racine du dépôt GitHub, puis active GitHub Pages sur la branche `main`.
