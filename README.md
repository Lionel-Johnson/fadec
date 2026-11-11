# FADEC ONG — Version institutionnelle premium (V2)

Site statique HTML / CSS / JavaScript, compatible GitHub Pages, sans build ni backend.

## Publication
1. Créer un dépôt GitHub public ou privé autorisant Pages.
2. Importer **le contenu** du dossier à la racine de la branche `main`.
3. Settings → Pages → Deploy from a branch → main / root.
4. Le site sera accessible à `https://utilisateur.github.io/nom-du-depot/`.

## Structure
- `index.html` : accueil premium
- `organisation.html`, `domaines.html`, `projets.html`, `actualites.html`, `rejoindre.html`, `soutenir.html`, `contact.html`
- `assets/style.css` : styles et design system
- `assets/main.js` : navigation, filtres, interaction contact

## Points à confirmer avant mise en production
- Dénomination officielle, logo, coordonnées, documents juridiques, photos de terrain et chiffres d'impact.
- Les photos sont des **illustrations externes** d'Unsplash, non des photos de FADEC.
- Les projets cités sont issus des archives du site ; leur statut actuel n'est pas confirmé.
- Le site statique n'enregistre pas de formulaires ni de dons. Le formulaire contact ouvre le logiciel de messagerie.
- Le monogramme typographique FADEC est provisoire et doit être remplacé par le logo officiel.
- Valider une politique de confidentialité avant toute collecte de données.

## Tests
Vérifier tous les liens, l'ergonomie mobile, le bon chargement des images externes, et les formulaires en conditions réelles avant toute publication définitive.


## Version V3 — Intégration de 10 visuels

- Tous les fichiers visuels fournis par le client ont été optimisés en WebP et placés dans `assets/images/`.
- Les 10 visuels sont consultables dans la galerie de la page d'accueil.
- Les visuels principaux ont été affectés aux sections : accueil, éducation, santé, environnement, état civil, projets, actualités et organisation.
- Le véritable logo FADEC est intégré à l'en-tête et au pied de page.
- L'ancien site WordPress n'est pas modifié.
- Les visuels IA sont des illustrations, non des archives photographiques.
- Le site de démonstration comporte `noindex` : retirer cette balise lors du lancement officiel et après validation.

### Publication GitHub Pages
Extraire ce dossier et importer **le contenu du dossier** (et non le dossier parent) à la racine de la branche `main`. Dans Settings > Pages, sélectionner Deploy from a branch, puis `main` et `/ (root)`.
