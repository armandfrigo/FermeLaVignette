# La Vignette — Site web

Site vitrine de la ferme familiale Walter Steiner à Montherod (Vaud).

## Structure

```
├── index.html      Page principale
├── css/style.css   Styles
├── js/main.js      Navigation mobile & animations
├── images/         Photos de la ferme
└── favicon.svg     Icône du site
```

## Déploiement (GitHub Pages)

1. Pousser le code sur la branche `main`
2. Sur GitHub : **Settings → Pages → Build and deployment**
3. Source : **Deploy from a branch**, branche **main**, dossier **/ (root)**
4. Le site sera disponible à : `https://armandfrigo.github.io/FermeLaVignette/`

## Développement local

Ouvrir `index.html` dans un navigateur, ou lancer un serveur local :

```bash
python -m http.server 8000
```

Puis visiter http://localhost:8000
