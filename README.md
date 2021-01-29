
### Description du jeu de données

Le jeu de données renseigne sur la situation hospitalières concernant l'épidémie de COVID-19.

Le fichier comporte:

Les données hospitalières relatives à l'épidémie du COVID-19 par **département et sexe du patient** : 
**Le nombre de patients hospitalisés, le nombre de personnes actuellement en réanimation ou soins intensifs, 
le nombre cumulé de personnes retournées à domicile, le nombre cumulé de personnes décédées.**

Après traitement des données, on va créer dans un fichier **data.py** toutes les fonctions avec les statistiques nécessaires pour les graphiques de l'API.On retourne le résultat 
sous format Json pour qu'elles soient lues correctement en page Html.
ces fonctions seront appelées dans le fichier **app.py**.Les données récupérées des fonctions seront stockées dans des variables HTML qui seront utilisées dans le fichier page.html.

On définit nos variables en indiquant l'option **safe** pour éviter les mauvaises injections et ajouter de la sécurité.

On définit également nos containers correspondant aux différents graphiques qui seront appelés dans le fichier JS graph.js. 

Dans le fichier graph.js, on trouve les différents container avec le code pour la création des graphiques.

<img src="http://www.monsite.com/image.png" alt="Zozor" />










