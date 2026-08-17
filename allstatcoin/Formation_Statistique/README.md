# Statistique Pour Data Analyst

Ce dépôt contient une série de notebooks Jupyter couvrant les concepts fondamentaux de statistiques pour l'analyse de données. Les notebooks sont organisés de manière progressive, allant des statistiques univariées aux analyses multivariées.

## 📋 Contenu

### Partie 1 - Statistique univariée
**Fichier :** `01_partie1_statistique_univariee.ipynb`

- Mesures de tendance centrale (moyenne, médiane, mode)
- Mesures de dispersion (variance, écart-type, étendue, coefficient de variation)
- Quartiles, quantiles, IQR et détection des outliers
- Analyse de la forme de la distribution (asymétrie, kurtosis)
- Analyse des variables qualitatives (effectifs, proportions, visualisations)
- Tests de normalité (Shapiro-Wilk, Kolmogorov-Smirnov, Q-Q plot)

### Partie 2 - Distributions de probabilité
**Fichier :** `02_Les_Distributions_de_proba.ipynb`

- Loi normale (distribution gaussienne)
- Fonction de densité de probabilité
- Paramètres de la distribution normale
- Applications en machine learning

### Partie 2 bis - Analyse de normalité
**Fichier :** `02_bis_Analyse_Normalite.ipynb`

- Tests approfondis de normalité
- Visualisations pour évaluer la normalité
- Interprétation des résultats

### Partie 3 - Échantillonnage et biais
**Fichier :** `03_echantillonnage_et_biais_dataset.ipynb`

- Concepts d'échantillonnage
- Identification et gestion des biais dans les datasets
- Méthodes d'échantillonnage

### Partie 4 - Statistique bivariée
**Fichier :** `04_bivariee.ipynb`

- Relations entre deux variables quantitatives (covariance, corrélation)
- Relations entre variables qualitatives et quantitatives
- Relations entre deux variables qualitatives (tables de contingence)
- Visualisations bivariées (scatter plots, boxplots, heatmaps)

### Partie 5 - Tests bivariés complets
**Fichier :** `05_bivarie_tests_complet.ipynb`

- Tests statistiques pour relations bivariées
- Tests d'hypothèses
- Interprétation des résultats de tests

### Partie 6 - Statistique multivariée (PCA)
**Fichier :** `06_statistique_multivariee_pca.ipynb`

- Analyse en composantes principales (PCA)
- Réduction de dimensionnalité
- Visualisation des composantes principales

## 🗂️ Structure du projet

```
Statistique_Pour_Data_Analyst/
├── README.md
├── 01_partie1_statistique_univariee.ipynb
├── 02_bis_Analyse_Normalite.ipynb
├── 02_Les_Distributions_de_proba.ipynb
├── 03_echantillonnage_et_biais_dataset.ipynb
├── 04_bivariee.ipynb
├── 05_bivarie_tests_complet.ipynb
├── 06_statistique_multivariee_pca.ipynb
└── ecommerce_dataset.csv
```

## 🔧 Prérequis

- Python 3.13 (ou version compatible)
- Jupyter Notebook ou JupyterLab
- Packages Python (voir section Installation)

## 📦 Installation

### 1. Cloner ou télécharger le dépôt

### 2. Installer les dépendances

Les packages suivants sont nécessaires :
- numpy
- pandas
- matplotlib
- scipy
- seaborn
- jupyter
- scikit-learn (pour PCA)

```bash
pip install numpy pandas matplotlib scipy seaborn jupyter scikit-learn
```

Ou installez directement depuis le fichier requirements.txt si disponible.

### 3. Lancer Jupyter Notebook

```bash
jupyter notebook
```

Ou avec JupyterLab :

```bash
jupyter lab
```

## 📊 Dataset

Le projet utilise le fichier `ecommerce_dataset.csv` qui contient des données d'e-commerce avec les variables suivantes :

- `client_id` : Identifiant unique du client
- `sexe` : Sexe du client
- `âge` : Âge du client
- `revenu_mensuel` : Revenu mensuel
- `segment_age` : Segment d'âge
- `revenu_cat` : Catégorie de revenu
- `produit` : Produit acheté
- `canal_achat` : Canal d'achat utilisé
- `montant_panier` : Montant du panier
- `panier_frequent` : Fréquence du panier
- `note_satisfaction` : Note de satisfaction
- `retour_produit` : Indicateur de retour produit
- `date_achat` : Date d'achat

## 🚀 Utilisation

1. Ouvrez les notebooks dans l'ordre numérique recommandé pour suivre la progression pédagogique
2. Exécutez les cellules dans l'ordre pour comprendre chaque concept
3. Modifiez les variables analysées pour explorer différentes facettes du dataset
4. Expérimentez avec les visualisations et les tests statistiques

## 📝 Notes

- Les notebooks sont conçus pour être pédagogiques et progressifs
- Chaque notebook contient des explications théoriques et des exemples pratiques
- Les visualisations sont intégrées pour faciliter la compréhension
- Les tests statistiques sont accompagnés d'interprétations détaillées

## 🔍 Concepts couverts

- Statistiques descriptives
- Tests de normalité
- Distributions de probabilité
- Échantillonnage et biais
- Analyse bivariée
- Tests d'hypothèses
- Analyse multivariée (PCA)
- Visualisation de données

## 📚 Ressources supplémentaires

Pour approfondir les concepts abordés, consultez :
- Documentation NumPy : https://numpy.org/doc/
- Documentation Pandas : https://pandas.pydata.org/docs/
- Documentation SciPy : https://scipy.org/
- Documentation Matplotlib : https://matplotlib.org/
- Documentation Seaborn : https://seaborn.pydata.org/

## 📄 Licence

Ce projet est destiné à des fins éducatives.

