# Projet Python - Analyse des Prix de Voitures

## Description
Ce projet analyse un ensemble de données de prix de voitures pour identifier les tendances du marché, les modèles de voitures les plus populaires, et d'autres informations pertinentes. L'objectif est de fournir des insights exploitables pour mieux comprendre le marché automobile et aider à la prise de décision.

## Contenu du Projet
Le projet contient un notebook Jupyter (`Projet_python1_.ipynb`) qui :
- Importe et nettoie les données.
- Effectue une analyse exploratoire des données (EDA) pour découvrir des tendances et des corrélations.
- Utilise des visualisations pour présenter les résultats de manière claire et concise.

## Jeux de Données
Le dataset utilisé dans ce projet provient d'une source de données fictive et contient les informations suivantes pour chaque voiture :
- `year`: Année de fabrication
- `make`: Marque du véhicule
- `model`: Modèle du véhicule
- `trim`: Version ou finition
- `body`: Type de carrosserie
- `transmission`: Type de transmission
- `vin`: Numéro d'identification du véhicule
- `state`: État ou province où la voiture a été enregistrée
- `condition`: État du véhicule (nouveau, d'occasion, etc.)
- `odometer`: Kilométrage du véhicule
- `color`: Couleur du véhicule
- `interior`: Couleur intérieure
- `sellingprice`: Prix de vente
- `saledate`: Date de la vente

## Installation
Pour exécuter ce projet en local, vous aurez besoin de :
1. Python 3.x installé sur votre machine.
2. Installer les dépendances requises via pip :
   ```bash
   pip install numpy pandas matplotlib
