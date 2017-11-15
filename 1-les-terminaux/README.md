# TP 1 - Les terminaux

## Objectifs
L'objectif général des tps de cette formation sera de reproduire la page d'accueil du site [AirBnb](https://www.airbnb.fr/) à l'aide des techniques de développement de page responsive vues au fil des chapitres.
Pour ce premier TP il s'agira de concevoir la structure html et CSS de la page qui nous servira de support pour le reste des TPS


## Préparatifs
*Vos développements devront toujours être testés en utilisant le protocole `http`, il faut pour cela utiliser un serveur web (ouvrir le fichier en double-cliquant dessus l'ouvrira dans le navigateur mais avec le protocole `file://` ce qui peut poser des problèmes de rendu).*
- Installer un serveur apache/php (sur windows [Apachefriends xampp](https://www.apachefriends.org/fr/index.html) ou [wampserver](http://www.wampserver.com/))
- Dans l'arborescence du serveur apache (dossier www ou htdocs) créer un sous-dossier pour ce TP, c'est dans ce dossier que vous créerez vos fichiers html et css.
- Récupérer le fichier `contenus.txt` présent dans ce dossier. Il contient tous les textes et les chemins des images qui sont utilisés sur la page (NB: il peut y avoir des différences entre les logements qui sont présentés sur le site airbnb et ceux du fichier au moment où vous réaliserez ce TP).

## Instructions
1. **Concevoir la structure html de la page en respectant la sémantique et en utilisant html5 (fichier html brut, sans styles).**<br>
Pour cette formation nous ne reproduirons que le début de la page (vous aurez remarqué que des contenus s'ajoutent au fur et à mesure que l'on scroll dans la page).<br>
*Bien entendu, pour que l'exercice soit intéressant, **il ne faut pas** examiner le code html/css du site airbnb.fr, sinon forcément, c'est de la triche* :open_mouth:<br>
Le code de la page doit être valide w3c : https://validator.w3.org/<br/>
les blocs à coder sont :
	- la barre de navigation avec le logo et les liens du menu
	- le header avec le titre du site et le formulaire de recherche (sans le formulaire détaillé qui s'affiche lorsque l'on met le focus dans le champ de saisie)
	- les bandeaux "Explorer Airbnb", "Expériences", "Logements" et "Destinations à la une"<br>
	- le footer<br>
	*NB: les flèches de navigation des sliders ne sont pas nécessaires*

2. **Coder les premiers styles de base du site (la mise en page sera réalisée dans les prochains TPs) :**
	- police de caractère, taille et couleur des texte
	- styles des boutons


## Pour aller plus loin
1. Intégrer une icon font comme [font-awesome](http://fontawesome.io/icons/) pour ajouter une icône "loupe" devant le formulaire de recherche.
2. Coder une fonction JavaScript qui détecte si l'utilisateur qui visite le site utilise ios ou android pour afficher un bandeau l'invitant à télécharger l'app ios ou android selon l'OS mobile dont il dispose. La détection de l'OS peut se faire grâce au User-Agent, qui peut être récupéré en JavaScript grâce à la propriété `navigator.userAgent` :
```js
console.log( navigator.userAgent );
```
