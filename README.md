# Portfolio — Lassiné Diomandé

Site statique (une seule page : `public/index.html`), hébergé sur Firebase Hosting.

## Déployer

```bash
npm install -g firebase-tools   # une seule fois
firebase login                  # une seule fois
firebase deploy --only hosting --project ID_DU_PROJET
```

## Modifier

Tout le contenu est dans `public/index.html`. Après une modification : `git add -A && git commit -m "maj" && git push`, puis relancer le déploiement.
