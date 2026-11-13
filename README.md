# Site public d'ARBOS – https://arbos.fr

Ce dépôt ne contient que la **mise en ligne** du site (`.github/workflows/deploy.yml`).
Le contenu est dans le dépôt de l'application `tikuna-qhispiyupanki/work-app` :

- `site/` : la page de présentation, le sondage, le contact et les mentions légales ;
- `scripts/build-site.mjs` : fabrique le site (présentation à la racine, démonstration dans `/demo/`).

Le site se met à jour tout seul chaque nuit, ou tout de suite avec « Actions → Mise en ligne du site arbos.fr → Run workflow ».
