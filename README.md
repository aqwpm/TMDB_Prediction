# TMDB_Prediction
L'objectif de ce travail est de construire un modèle prédictif capable de prédire les revenus mondiaux au box-office d'un film en utilisant un ensemble de métadonnées associées. 

Nous aborderons ce sujet en suivant une méthode systématique :
 - Analyse exploratoire des données (EDA) et prétraitement de l'ensemble de données pour en comprendre la structure, les relations et les anomalies.
 - Ingénierie des caractéristiques: Utilisation des caractéristiques existantes pour en extraire ou combiner de nouvelles informations qui pourraient être utiles pour la prédiction.
 - Suivi de la performance et arrêt anticipé: Ceci afin d'éviter les problèmes de surajustement du modèle. Nous examinerons également l'importance des variables pour vérifier si les variables en cours d'observation sont logiques.
 - Réglage des paramètres des modèles et la modélisation: Pour optimiser leurs performances.
 - Comparaison de différents modèles(LightGBM et XGBoost): Utilisation de métriques telles que le RMSE pour évaluer et comparer les performances de différents modèles.

**tmdb-prediction.ipynb** : Input, dans lequel il y a tous mes codes

**TMDB_Prediction.pdf** : Le rapport qui aide à mieux comprendre le code

**train_new.csv, test_new.csv** : Output, les nouvelles caractéristiques générées sont ajoutées au DataFrame originaux, et sont retournées sous la forme de train_new et test_new, ils sont puis sauvegardés sous format .csv

**predicted_revenue.csv** : Output, prédiction sortie par le modèle LightGBM

**predicted_revenue_xgb.csv** : Output, prédiction sortie par le modèle XGBoost

**combined_predictions_and_real.csv** : Output, prédictions sorties par les deux modèles respectivement, puis comparer avec les vraies valeurs
