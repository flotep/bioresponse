# Prédire la réponse biologique d'une molécule à partir de ses propriétés physico-chimiques 

Compétition Kaggle : https://www.kaggle.com/c/bioresponse/overview

L'objectif de la compétition est de construire un modèle aussi bon que possible afin de permettre, 
de la manière la plus optimale que le permettent ces données, de relier les informations d'une molécule à une réponse biologique réelle.

Les données partagées sont au format CSV. Chaque ligne de cet ensemble de données représente une molécule. 
La première colonne contient des données expérimentales décrivant une réponse biologique réelle ; la molécule a été vue comme provoquant cette réponse (1) ou non (0). 
Les autres colonnes représentent les descripteurs moléculaires (d1 à d1776). 
Il s'agit de propriétés calculées qui peuvent saisir certaines des caractéristiques de la molécule, par exemple sa taille, sa forme ou sa constitution élémentaire.  
Les probabilités prédites qu'une molécule suscite une réponse sont évaluées à l'aide de la métrique de perte logisique (log loss).



