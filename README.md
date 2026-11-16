# Cétofine 21 · Advertorial comparatif (aperçu de relecture Convtek)

Article sponsorisé "Régime protéiné après 50 ans : seule, en sachets ou avec un programme ? Le comparatif complet",
publié sur le média en marque blanche **Juste Mesure** (nom de travail).

Aperçu : https://convtek.github.io/lp-cetofine21-advertorial/

- Copie de relecture uniquement : `noindex, nofollow`, `robots.txt` en `Disallow: /`
- Canonique, og:url et og:image pointent sur l'adresse github.io (à réécrire sur le domaine du média à la mise en ligne)
- Les boutons envoient vers les fiches cetofine.com avec `utm_source=justemesure&utm_medium=advertorial&utm_campaign=regime-proteine-comparatif`
  et un `utm_content` par emplacement ; les paramètres d'une annonce (fbclid, gclid, utm_*) sont recopiés en priorité
- Ce dépôt ne contient que le build. Sources : `Convtek OS/05-Exports/cetofine21-advertorial-femme50`

## Avant une vraie mise en ligne
- Nom et domaine du média, page Mentions légales (éditeur du site), politique de confidentialité
- Mention "Photographie retouchée" si les photos de Nathalie le sont
- Pixel / GTM et API du tracker Convtek

## Republier après une modification

Depuis `05-Exports/cetofine21-advertorial-femme50` :

```
npm run build
```

puis copier le contenu de `dist/` ici sans écraser `README.md`, `.nojekyll` ni `robots.txt`,
remettre dans `index.html` la canonique, og:url et og:image github.io, commit et push sur `main`.
