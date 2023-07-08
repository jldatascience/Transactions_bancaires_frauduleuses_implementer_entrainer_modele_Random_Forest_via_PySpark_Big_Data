# Traitement de données massives (Big Data) avec PySpark

# Détection d’anomalies (transactions bancaires frauduleuses) : implémenter, entraîner et comparer la performance d'un modèle de Random Forest & de régression logistique





## Objectif

Ce use case consiste à implémenter, tester et comparer la performance de 2 algorithmes (forêts aléatoires & régression logistique) avec PySpark, pour faire de la détection de transaction frauduleuses.






## Description du jeu de données

Le jeu de données porte sur les paramètres pour classer les transactions bancaires.

Il contient les transactions effectuées en septembre 2013 par les titulaires de cartes bancaires européennes : 492 transactions frauduleuses sur 284 807 transactions.

L'ensemble de données est très déséquilibré, les classes positives (fraudes) représentent 0,172% de toutes les transactions.

Les variables explicatives (features) sont stockées dans les trente premières colonnes et les variables cibles (labels) dans la dernière colonne





## Description de l'algorithme Random Forest

Les forêts aléatoires sont composées d'un ensemble d'arbres décisionnels.
Ces arbres se distinguent les uns des autres par le sous-échantillon de données sur lequel ils sont entraînés.
Ces sous-échantillons sont tirés au hasard dans le jeu de données initial.
Le principe de fonctionnement des forêts aléatoire est simple : de nombreux petits arbres de classification sont produits sur une fraction aléatoire de données.
Random Forest fait voter les arbres de classification afin de déduire l'ordre et l'importance des variables explicatives.




## Démarche 

Cf. le notebook ci-joint.



## Conclusion

Le modèle de régression logistique est plus performant que le Random forest.
