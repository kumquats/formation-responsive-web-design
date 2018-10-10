# TP 3 - Media Queries

## Objectifs
Améliorer la mise en page pour tablette + desktop, et le support de l'impression à l'aide des Media Queries.


## Préparatifs
- reprendre les fichiers du tp précédent ou repartir des fichiers fournis dans ce dossier.


## Instructions
1. **Ajouter une balise `viewport` pour la prise en charge correcte des Media Queries.**
2. **En paysage, le menu ne doit pas être en position fixed (pour gagner de l'espace en hauteur)**
3. **Coder la version desktop (width > 1024) :**
	- ajuster la taille des textes
	- afficher le menu et masquer la flèche à côté du logo
	- afficher le bouton d'envoi du formulaire


## Pour aller plus loin
5. **Créer une Media Query print**
- Masquer la nav et le formulaire de recherche
- Passer la taille de base du texte à 12pt
- Préciser les marges d'impression à l'aide de
```css
@page {
margin: 0.5cm;
}
```
- Empêcher les titres d'être séparés de leurs contenus à l'aide des instructions CSS :
```css
page-break-after:avoid;
page-break-inside:avoid
```
Source :
https://getflywheel.com/layout/how-to-style-your-website-for-print-with-css/
https://caniuse.com/#feat=css-paged-media

6. **Ajouter une Media Query Level 4 pour ajouter des effets de roll-over aux périphériques qui le gèrent (non tactiles).**


