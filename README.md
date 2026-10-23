Problématique. Le prix d’une voiture d’occasion dépend de nombreux facteurs : âge, kilométrage, marque, motorisation, puissance, équipements. Notre question de recherche est la suivante : quelles caractéristiques d’un véhicule expliquent le mieux son prix, et dans quelle mesure peut-on le prédire ? Nous voulons à la fois prédire le prix avec la plus faible erreur possible, et identifier les variables qui l’influencent réellement.

Données. Aucune base ne contient toutes les informations nécessaires. Nous construisons donc notre propre jeu de données à partir de quatre sources : le jeu Automobile du UCI Machine Learning Repository (archive.ics.uci.edu/dataset/10/automobile), et trois jeux de voitures d’occasion trouvés sur Kaggle [préciser les noms]. Dans chaque base, nous ne gardons que les colonnes utiles pour expliquer le prix.

Nettoyage. Pour chaque base, nous corrigeons les types, harmonisons les libellés et les unités, supprimons les doublons, traitons les valeurs aberrantes et les valeurs manquantes, en documentant chaque choix.

Fusion. Les bases nettoyées sont regroupées en une seule table finale grâce à des clés communes (marque, modèle, année, carburant).

Modélisation. Nous entraînons d’abord une régression linéaire comme référence, puis des modèles plus flexibles (forêt aléatoire, gradient boosting). Nous suivons deux approches. Dans la première, nous testons plusieurs combinaisons de colonnes et retenons la plus pertinente. Dans la seconde, nous fixons les colonnes à l’avance. Nous comparons ensuite les résultats des deux approches.