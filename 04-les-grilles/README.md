# TP 4 - Les grilles

## Objectifs
Mettre en place une grille CSS pour gérer l'affichage en colonne des différents éléments de la page.


## Préparatifs
- reprendre les fichiers du tp précédent ou repartir des fichiers fournis dans ce dossier.


## Instructions
1. **Utiliser les propriétés flexbox vues en formation pour afficher les différents éléments de la page en version mobile**
	- il n'y a pas besoin de grille pour cette partie, des largeurs en pourcentage doivent suffire
	- prendre soin de bien intégrer des marges entre les éléments
	- la mise en page sera un peu différente de la version mobile d'airbnb qui affiche les éléments dans un slider, de notre côté nous allons toujours afficher tous les éléments avec les ajustements suivants :
		- les liens de la section "Explorer Airbnb" passent les uns en dessous des autres
		- les blocs de la section "Expériences" s'affichent par lignes de 2
		- les blocs de la section "Logements" s'affichent les uns en dessous des autres (1 bloc par ligne)
		- les blocs de la section "Destinations à la une" s'affichent par rangées de 3
2. **Utiliser une grille basée sur flexbox pour générer la version desktop afin d'obtenir un affichage similaire à celui de la page d'accueil d'Airbnb**
	- la grille sera basée sur 12 colonnes ce qui permettra d'obtenir des lignes de 12, 6, 4, 3, 2 et 1 blocs.
	- utiliser les media queries existantes
	- Pour que la propriété `flex-grow` donne le résultat attendu, vous aurez à utiliser la propriété `flex-basis:0;`

## Pour aller plus loin
3. **Reproduire la grille avec les CSS Grids**
