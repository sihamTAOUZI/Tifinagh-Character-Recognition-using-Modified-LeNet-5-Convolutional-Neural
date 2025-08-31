# Tifinagh-Character-Recognition-using-Modified-LeNet-5-Convolutional-Neural
Ce TP avait pour objectif de mettre en œuvre un réseau de neurones convolutif pour la reconnaissance des caractères manuscrits Tifinagh.
Les étapes principales incluaient :

Préparation et exploration du dataset AMHCD : chargement des images, visualisation d’exemples et organisation des classes.

Prétraitement des images : redimensionnement à 32×32 pixels et normalisation sur trois canaux pour traiter des images RGB.

Construction d’un modèle CNN basé sur LeNet-5 : adaptation du modèle original pour 33 classes de caractères, avec deux couches convolutionnelles, deux couches de pooling et trois couches entièrement connectées.

Entraînement et évaluation du modèle : utilisation de l’optimiseur Adam, suivi des courbes de loss et accuracy, et évaluation sur les ensembles validation et test.

Analyse des résultats : génération de la matrice de confusion normalisée, calcul du rapport de classification (précision, rappel, F1-score) et interprétation des confusions entre caractères similaires.

Ce TP a permis de comprendre la mise en œuvre pratique d’un CNN, le traitement d’images manuscrites multicanaux, ainsi que l’évaluation et l’interprétation des performances d’un modèle de classification multi-classes.
