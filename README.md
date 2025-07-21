# Simulateur d'évaluation immobilière - SalesHouses

## 🏛þ Présentation du projet

Ce projet vise à développer un **simulateur intelligent** permettant d'estimer le **prix de vente d'un appartement** au Maroc, à partir de ses caractéristiques (surface, ville, nombre de pièces, équipements, etc.). L'objectif est de construire un modèle de régression supervisé entraîné sur des données réelles.

## 🔄 Fonctionnalités principales

* Analyse exploratoire et nettoyage des données
* Prétraitement : encodage, imputation, scaling
* Entraînement de plusieurs modèles de régression (Linear, RandomForest, SVR, GBoost)
* Validation croisée et tuning des hyperparamètres
* Sauvegarde du modèle final pour intégration web

## 📂 Structure du projet

```
sales_house_modele_supervise/
├── appartements_data .csv         # Fichiers de données (CSV)
├── model.pkl                      # Modèle sauvegardé (model.pkl)
├── script.ipynb                   # Scripts Python           
├── README.md                      # Ce fichier
```

## ⚖️ Librairies utilisées

* pandas, numpy
* matplotlib, seaborn
* scikit-learn
* joblib

## 📆 Instructions d’exécution

1. Cloner le repo :

```bash
git clone https://github.com/r00tMG/sales_house_modele_supervise.git
cd sales_house_modele_supervise
```

2. Créer un environnement virtuel et l’activer :

```bash
python -m venv .venv
source .venv/bin/activate  
```

3. Installer les dépendances :

```bash
pip install -r requirements.txt
```

4. Lancer le notebook principal :

```bash
jupiter-lab
```

## 📊 Résultats attendus

* Précision : R2 > 0.80
* Faible erreur : RMSE < seuil du marché
* Intégrabilité backend/web via `model.pkl`

## 📅 Suivi Agile (Github Projects)

* Organisation en sprints
* Epics : Data cleaning, Model Training, Evaluation, Packaging
* Outils : Kanban, backlog, daily meetings

