# Projet de prédiction de sinistralité automobile – data cleaning, économétrie, machine learning (XGBoost, MLP)

Ce projet a été réalisé dans le cadre d’un module d’analyse de données appliquée à l’assurance. Il vise à modéliser à la fois la **fréquence** et le **montant** des sinistres automobiles, à partir de données enrichies par des variables contractuelles, géographiques et climatiques.

## Objectifs du projet

- Comprendre les **déterminants de la sinistralité** (fréquence & gravité)
- Appliquer des **modèles économétriques** (GLM, logit)
- Tester plusieurs modèles de **Machine Learning** pour la prédiction :
  - XGBoost
  - LightGBM
  - Réseau de neurones (MLP)
  - MLP avec transformation logarithmique de la variable cible

## Contenu du dépôt

| Fichier                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `data_econometrie.ipynb` | Préparation des données, analyse descriptive, estimation GLM et logit       |
| `data_ml.ipynb`          | Modèles XGBoost / LightGBM / MLP pour la prédiction de `claim_amount`       |
| `README.md`              | Présentation du projet                                                      |
| `*.pdf`                  | Versions PDF des livrables                                                  |

## Outils utilisés

- Python
- pandas, numpy
- scikit-learn
- xgboost, lightgbm
- tensorflow / keras
- statsmodels
