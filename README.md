# Site public d'ARBOS – https://arbos.fr

Ce dépôt ne contient que la **mise en ligne** du site (`.github/workflows/deploy.yml`).
Le contenu est dans le dépôt de l'application `tikuna-qhispiyupanki/work-app` :

- `site/` : la page de présentation, le sondage, le contact et les mentions légales ;
- `scripts/build-site.mjs` : fabrique le site (présentation à la racine, démonstration dans `/demo/`).

Le site se met à jour tout seul chaque nuit, ou tout de suite avec « Actions → Mise en ligne du site arbos.fr → Run workflow ».

Mettre en ligne tout de suite depuis l'environnement de travail : un envoi (commit) sur ce dépôt relance aussi la mise en ligne.

Le dépôt de l'application est **privé** (14/11/2026) : la mise en ligne le lit avec le secret `WORK_APP_TOKEN` de ce dépôt
(jeton GitHub « arbos-site lit work-app », lecture seule sur work-app, sans expiration). Sans lui, le site ne se met plus à jour
(il reste en ligne tel quel).
