# Anticiper les besoins en consommation de batiments
## Description
Projet OpenClassrooms sur la prédiction de la consommation d'energie et d'émissions de CO2 de batiments a partir d'informations relatives aux batiments
* Les données sont disponibles sur [ce lien](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P4/2016_Building_Energy_Benchmarking.csv)

Le projet est divises en 4 parties
* Le notebook **ElHouri_Marwa_1_notebook_exploratoire_07_2022** contient le netoyage et l'analyse exploratoire des données
* Les notebooks **ElHouri_Marwa_2_ notebook_prediction_emission_sans_ENERGYSTARScore_07_2022** et 
**ElHouri_Marwa_3_ notebook_prediction_emission_avec_ENERGYSTARScore_07_2022** présentent les recherches de la meilleure méthode de regression 
et l'interpretation des résultats pour l'émission de CO2 avec et sans l'indicateur ENERGYSTARScore.
Cela permet d'étudier la pertinence de cet indicateur pour la prédiction.
* Le notebook **ElHouri_Marwa_4_prediction_consommation_07_2022** présente les recherches de la meilleure méthode de regression 
et l'interpretation des résultats pour la consommation d'énergie dans les batimements.
* Le fichier pdf **ElHouri_Marwa_5_presentation_07_2022** est la présentation du projet.
## Notions traitées
* Nettoyage des données
* Utilisation de la librairie **Feature Engine** pour la selection des variables
* Analyse exploratoire
* Transformation des variables (StandardScaler, FunctionTransformer, BackwardDifferenceEncoder, ..)
* Etudes des méthodes de regression (Lineaire (Ridge, Lasso), Decision Tree, Random Forest, XGBoost)
* Recherches d'hyperparamètres (GridSearchCV, RandomizedSearchCV)
* Etude de performance
* Feature Importances et interpretabilité locale des résulats (LIME)

