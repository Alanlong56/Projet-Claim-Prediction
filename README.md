Projet de prédiction de sinistralité automobile – data cleaning, économétrie, machine learning (XGBoost, MLP)
Ce projet a été réalisé dans le cadre d’un module d’analyse de données appliquée à l’assurance. Il vise à modéliser à la fois la fréquence et le montant des sinistres automobiles, à partir de données assurantielles enrichies par des variables climatiques et contractuelles.

Objectifs du projet
Comprendre les déterminants de la sinistralité (fréquence & gravité)
Appliquer des méthodes économétriques (GLM, logit) sur la fréquence
Tester des modèles de Machine Learning pour prédire le montant d’un sinistre :
XGBoost
LightGBM
Réseau de neurones (MLP)
Réseau de neurones avec transformation logarithmique
Contenu du dépôt
Fichier	Description
data_econometrie.ipynb	Préparation des données, analyse descriptive, GLM, logit
test.ipynb	Classification avec XGBoost (has_claim), prédiction du montant (claim_amount) avec XGBoost, LightGBM et MLP
Outils utilisés
Python
pandas, numpy
scikit-learn
xgboost, lightgbm
tensorflow / keras
statsmodels
