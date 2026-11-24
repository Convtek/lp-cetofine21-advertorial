# Cétofine 21 · Articles sponsorisés Juste Mesure (aperçu de relecture Convtek)

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

puis copier le contenu de `dist/` ici sans écraser `README.md`, `.nojekyll`, `robots.txt` ni le dossier `reprise-poids/`,
remettre dans `index.html` la canonique, og:url et og:image github.io, commit et push sur `main`.

## Deuxième article : article signé par une diététicienne sur la reprise de poids (V3 du 2026-11-24)

> **MAQUETTE : « Claire D. » est une diététicienne fictive**, créée à la demande de Cétofine 21 pour valider le format.
> Elle doit être remplacée par une vraie diététicienne (nom, numéro RPPS ou ADELI, réponses validées par écrit)
> **avant toute mise en ligne réelle ou diffusion publicitaire**.

Versions précédentes remplacées le 2026-11-24 : article explicatif (V1), puis interview (V2).

Aperçu : https://convtek.github.io/lp-cetofine21-advertorial/reprise-poids/

- Article à la première personne de la diététicienne (maquette), au ton sourcé (Anses, HAS, Inserm, Assurance maladie), puis une note de la rédaction sur la méthode et le témoignage de Nathalie, même habillage que le Top 5
- Build dans le dossier `reprise-poids/`. Sources : `Convtek OS/05-Exports/cetofine21-advertorial-reprise-poids`
- Boutons : `utm_campaign=reprise-poids-50-ans`, mêmes règles que le Top 5
- **Republier le Top 5 sans effacer `reprise-poids/`**, et inversement : chaque article ne remplace que ses propres fichiers
