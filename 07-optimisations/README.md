# TP 7 - Optimisations

## Objectifs
Mettre en oeuvre quelques techniques d'optimisation de la page.


## Préparatifs
- reprendre les fichiers du tp précédent ou repartir des fichiers fournis dans ce dossier.


## Instructions
1. **concaténer les css pour réduire le nombre de requêtes http**
	- télécharger la css source de bootstrap (non minifiée) en local
	- concaténer ensuite la css de bootstrap avec votre main.css
	- sous unix il est possible d'utiliser la commande `cat` :
	```bash
	cat one.css two.css three.css > bundle.css
	```
	- sous windows c'est la commande `type` qui permet de le faire :
	```bash
	type one.css two.css three.css > bundle.css
	```
2. **minifier la css concaténée pour réduire le poids du fichier**
	- pour un outil en ligne, vous pouvez utiliser http://www.mattbasta.com/crass/ ou encore https://www.cleancss.com/css-minify/
	- pour un outil en ligne de commande, se référer à la page http://goalsmashers.github.io/css-minification-benchmark/ (benchmark des différents outils)
	- mettre le résultat de la minification dans le fichier `bundle.min.css`
	- comparer le poids du fichier non minifié `bundle.css`et de celui minifié `bundle.min.css`
	- dans le fichier html, inclure `bundle.min.css` à la place des deux autres et s'assurer que tout fonctionne toujours !
3. **Améliorer la version print en affichant les urls des liens**
	- une fois les modifications faites, il faudra re-concaténer et re-minifier les css !
	- d'où l'intérêt de scripts npm, gulp, ou webpack.