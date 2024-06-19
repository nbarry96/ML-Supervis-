# Prédiction des ventes hebdomadaires de la société Walmart.
## Inroduction
Walmart Inc., une entreprise américaine de renom, est une géante de la vente au détail opérant à l'échelle mondiale. Fondée en 1962 par Sam Walton, elle est basée à Bentonville, dans
l'Arkansas.
Ce projet a pour objectif de développer un modèle de machine learning capable de prédire les ventes hebdomadaires des magasins avec une précision maximale. Un tel modèle permettra de mieux comprendre l'impact des indicateurs économiques sur les ventes et servira de base pour planifier les futures campagnes marketing.

## Structure du projet
- **walmart_project_supervised_ifpass.csv**: Contient les données du projet.
- **Notebook_ML**: Contient les notebooks Jupyter.
- **requirements.txt**: Fichier listant les dépendances du projet.
- **README.md**: Fichier de documentation du projet.

## Prérequis - Installations
* Avoir un éditeur de code (Visual Studio Code par exemple)
* Installer les packages requis
```bash
pip install -r requirements.txt
```
## I. Dossier du projet
Clonez ce dépôt pour créer votre dossier de projet :

`git clone https://github.com/nbarry96/ML-Supervis-.git`

Placez-vous dans le répertoire du projet **Supervised_ML** :

```bash
cd ML_Supervis-
```

## II. Exécution
Exécuter le notebook `Notebook_ML.ipynb` dans un éditeur de code.

## III.Description des données
Le jeu de données initial contient 6435 entrées et comporte 9 variables. Ces variables
incluent :

Store | Date | Weekly_Sales | Holiday_Flag | Temperature | Fuel_Price | CPI | Unemployment | Unnamed 
|--------------|-------------|-----------------|-----------------|-----------------|----------------|-----------|----------------|-----------|
## IV. Source de données
Le jeu de données utilisé pour ce projet est fourni par Jedha Bootcamp. Vous ppouvez le télécharger en suivant ce [lien]()

## V. Prétraitement des données
* Suprression de la colonne "Unnamed"
* Suprression de la colonne "Date" et création de nouvelles colonnes `Year`, Month`, `Day` et `Day_Of_Week`.
* Elimination de toutes les entrées manquantes de la variable cible "Weekly_Sales".
* Filtre des valeurs aberrantes dans les colonnes `Temperature`, `Fuel_Price`, `CPI` et`Unemployment`.

## VI. Modèles de ML
* Régression linéaire simple
* Régression linéaire régularisée
* Random Forest Regressor

## VII. Author
Nene Oumou BARRY

