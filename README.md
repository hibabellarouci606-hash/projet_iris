
# Classification des Fleurs d'Iris
"# Projet : Classification des Fleurs d’Iris

Contexte
Ce projet s’inscrit dans le cadre du module Logiciels Libres et Open Source (LLOS), niveau Master 1 (Microbiologie appliquée, Biochimie appliquée, Parasitologie, Biotechnologie et valorisation des plantes).
Il illustre la mise en place d’un workflow de recherche reproductible en utilisant Git/GitHub, Jupyter Notebook et des bibliothèques Python pour l’analyse de données.

Objectif du projet
L’objectif principal est de construire un modèle de classification capable de prédire l’espèce d’une fleur d’Iris à partir de ses caractéristiques morphologiques.
Les trois espèces à distinguer sont : Iris setosa, Iris versicolor et Iris virginica.

Description du jeu de données
Le jeu de données Iris est un classique de l’apprentissage automatique, contenant 150 échantillons de fleurs répartis en trois espèces.
Chaque échantillon est décrit par quatre caractéristiques continues (en cm) : longueur et largeur du sépale, longueur et largeur du pétale.

Outils et technologies utilisés
Langage : Python

Environnement : Jupyter Notebook

Bibliothèques principales : NumPy, Pandas, Matplotlib, Seaborn, scikit-learn

Gestion de versions : Git (local)

Hébergement du code : GitHub (remote)

Structure du projet
donnees/ : fichiers de données brutes ou externes (si nécessaires)

notebooks/ : notebooks Jupyter, notamment Iris_Classification.ipynb

scripts/ : scripts Python supplémentaires (si nécessaires)

resultats/ : sorties, graphiques, fichiers .csv des prédictions

README.md : description du projet et consignes générales

Étapes principales de l’analyse
Importation des bibliothèques Python nécessaires.

Chargement et mise en forme du jeu de données Iris dans un DataFrame Pandas.

Analyse exploratoire des données (statistiques descriptives, visualisations, répartition des espèces).

Préparation des données pour la modélisation (séparation X/y, division train/test, standardisation).

Entraînement d’un modèle de classification K-Nearest Neighbors (KNN).

Évaluation du modèle (précision, matrice de confusion, rapport de classification).

Sauvegarde des prédictions dans un fichier resultats/predictions_iris.csv.

Travail attendu
Un dépôt GitHub contenant :

La structure du projet (donnees/, notebooks/, scripts/, resultats/, README.md).

Le notebook complet Iris_Classification.ipynb (code + commentaires + visualisations).

Un historique Git montrant les différentes étapes du développement (commits).

Ce projet a pour but de vous familiariser avec les bonnes pratiques de recherche reproductible, de versionnement avec Git et de documentation claire d’une analyse de données."
​
