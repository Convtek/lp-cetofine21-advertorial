# Cétofine 21 · Top 5 des meilleurs régimes après 50 ans (aperçu de relecture Convtek)

Article sponsorisé "Top 5 des meilleurs régimes pour les femmes de plus de 50 ans en 2026" (remplace le comparatif "seule / sachets / programme" depuis le 2026-11-18),
publié sur le média en marque blanche **Juste Mesure** (nom de travail).

Aperçu : https://convtek.github.io/lp-cetofine21-advertorial/

- Copie de relecture uniquement : `noindex, nofollow`, `robots.txt` en `Disallow: /`
- Canonique, og:url et og:image pointent sur l'adresse github.io (à réécrire sur le domaine du média à la mise en ligne)
- Les boutons envoient vers les fiches cetofine.com avec `utm_source=justemesure&utm_medium=advertorial&utm_campaign=top5-regimes-50-ans`
  et un `utm_content` par emplacement ; les paramètres d'une annonce (fbclid, gclid, utm_*) sont recopiés en priorité
- Ce dépôt ne contient que le build. Sources : `Convtek OS/05-Exports/cetofine21-advertorial-top5` (ancienne version : `cetofine21-advertorial-femme50`)

## Avant une vraie mise en ligne
- Nom et domaine du média, page Mentions légales (éditeur du site), politique de confidentialité
- Mention "Photographie retouchée" si les photos de Nathalie le sont
- Pixel / GTM et API du tracker Convtek

## Republier après une modification

Depuis `05-Exports/cetofine21-advertorial-top5` :

```
npm run build
```

puis copier le contenu de `dist/` ici sans écraser `README.md`, `.nojekyll` ni `robots.txt`,
remettre dans `index.html` la canonique, og:url et og:image github.io, commit et push sur `main`.
