# Immobilier

## Description

Ce projet vise à prédire la valeur foncière des propriétés en fonction de plusieurs variables explicatives, notamment des taxes et des caractéristiques physiques des biens immobiliers. L'étude se concentre sur l'impact des taxes locales sur la valeur foncière des propriétés dans différents départements français.

## Objectif de l'étude

L'objectif principal de cette étude est de prédire la valeur foncière des propriétés en fonction de plusieurs variables explicatives, notamment :
- **CFE_moyen** : Cotisation Foncière des Entreprises (CFE), qui est une taxe sur les biens immobiliers utilisés par les entreprises.
- **IFER_moyen** : Imposition Forfaitaire sur les Entreprises de Réseaux (IFER), une taxe appliquée aux entreprises exploitant des infrastructures de réseau.
- **TFPNB_moyen** : Taxe Foncière sur les Propriétés Non Bâties, qui s'applique aux terrains non construits.
- **Taxe_habit_moyen** : Taxe d'habitation, une taxe locale appliquée aux occupants de logements.
- **surface_reelle_bati** : Surface réelle du bâtiment.
- **nombre_pieces_principales** : Nombre de pièces principales dans le bâtiment.
- **nombre_lots** : Nombre de lots associés à la propriété.

L'étude vise à quantifier l'influence de ces variables sur la valeur foncière des propriétés, avec un accent particulier sur l'impact des taxes locales.

## Contenu du Projet

Le projet est structuré comme suit :

1. **Importation des packages nécessaires** : Les bibliothèques utilisées incluent `requests`, `pandas`, `geopandas`, `matplotlib`, `folium`, `seaborn`, `math`, `IPython.display`, `numpy`, et divers modules de `sklearn` pour la modélisation.
2. **Téléchargement et chargement des données** : Les données sont téléchargées depuis une URL et chargées dans un DataFrame pandas.
3. **Prétraitement des données** : Nettoyage des données, gestion des valeurs manquantes, sélection des colonnes pertinentes et fusion avec les données de taxes.
4. **Analyse exploratoire des données (EDA)** : Visualisation des données, analyse des valeurs manquantes, et création de tableaux de corrélation et de nuages de points.
5. **Détection et gestion des outliers** : Identification et traitement des valeurs aberrantes pour améliorer la qualité des prédictions.
6. **Modélisation prédictive** : Utilisation de divers modèles de machine learning pour prédire la valeur foncière.

## Installation

Pour exécuter ce projet, vous aurez besoin des bibliothèques Python suivantes :
- requests
- pandas
- geopandas
- matplotlib
- folium
- seaborn
- numpy
- scikit-learn
- statsmodels
- xgboost

Vous pouvez installer ces bibliothèques en utilisant pip :

```bash
pip install requests pandas geopandas matplotlib folium seaborn numpy scikit-learn statsmodels xgboost
```
# Auteur
- KAFFAF Hicham
