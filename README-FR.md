# Prédiction de performances athlétiques — 1500m en athlétisme

## Aperçu
Ce projet a été développé dans le cadre d’une compétition en science des données visant à prédire le **meilleur temps personnel d’un athlète sur 1500 mètres** à partir de ses performances sur d’autres distances et de ses caractéristiques démographiques.

L’objectif est d’explorer et d’évaluer différents **modèles de régression supervisée** afin d’identifier celui qui offre les prédictions les plus précises et les plus stables dans un contexte réel d’analyse sportive.

---

## Méthodologie
Une approche expérimentale et comparative a été adoptée pour évaluer plusieurs algorithmes d’apprentissage supervisé, notamment :

- **Régression linéaire**  
- **Arbre de décision**  
- **Forêt aléatoire (Random Forest)**  
- **Gradient Boosting**  
- **K plus proches voisins (KNN)**  
- **Régression par vecteurs de support (SVR – noyau RBF)**  
- **Réseaux de neurones**

La performance des modèles a été mesurée à l’aide de métriques standard telles que **RMSE**, **MAE** et **RMSE en validation croisée (CV RMSE)** afin d’évaluer à la fois la précision et la capacité de généralisation.

---

## Résultats
Bien que le **Gradient Boosting** ait obtenu le RMSE le plus faible sur l’ensemble de test (~2999), la **Forêt aléatoire (Random Forest)** s’est révélée plus stable et généralisable, avec une variance de RMSE en validation croisée de seulement **63 %**, contre **114 %** pour le Gradient Boosting.

Ces résultats démontrent que **Random Forest** offre un meilleur équilibre entre précision et robustesse, en faisant le modèle le plus fiable pour la prédiction des temps sur 1500 m.

---

## Points clés
- Importance de l’équilibre entre précision et généralisation des modèles  
- Influence de la préparation et de la mise à l’échelle des données sur la performance  
- Comparaison des méthodes d’ensemble appliquées à la prédiction sportive

---

## Technologies utilisées
- **Python**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Scikit-learn** (entraînement et évaluation des modèles)  
- **Jupyter Notebook**

---
## Ouvrir dans Google Colab

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hM8jqgeYr4qNzStI76BrCJhZ5q1DFqGl?usp=sharing)

Je recommande de le visualiser sur google colab pour optenir une meilleure visualisation de l'évaluation des performances.

---

## Auteur
**Sophie Mercier**  
AEC en Internet des Objets et Intelligence Artificielle  
