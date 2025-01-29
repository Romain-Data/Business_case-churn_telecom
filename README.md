# 📊 Prédiction du Churn dans le Secteur des Télécoms

## 📌 Objectif du Projet

L'objectif de ce projet est d'identifier les clients susceptibles de résilier leur abonnement (churn) en analysant leurs caractéristiques et comportements à partir d'un fichier client. Un score de risque est attribué à chaque client afin que l'entreprise puisse cibler ceux à forte probabilité de résiliation et leur proposer des offres personnalisées pour améliorer leur fidélisation.

## 📂 Structure du Repository

📁 Business_case-churn_telecom

│── 📄 requirements.txt   # Bibliothèques nécessaires pour exécuter le projet

│── 📄 dataset.csv        # Fichier de données client

│── 📄 churn_analysis.ipynb  # Notebook Jupyter avec l'analyse et le modèle ML

## ⚙️ Installation et Configuration

1. Cloner le repository

`git clone https://github.com/Romain-Data/Business_case-churn_telecom.git`

`cd churn-telecom`

2. Créer un environnement virtuel (optionnel mais recommandé)

`python -m venv venv`

`source venv/bin/activate  # Pour Mac/Linux`

`venv\Scripts\activate    # Pour Windows`

3. Installer les dépendances

`pip install -r requirements.txt`

Lancer Jupyter Notebook

jupyter notebook

Puis ouvrir le fichier notebook.ipynb.

## 🧑‍💻 Modélisation du Churn

Actuellement, le projet utilise un modèle de régression logistique pour identifier les clients à risque. Ce modèle sera amélioré avec d'autres algorithmes de classification

## 📈 Prochaines Améliorations

✅ Comparaison de plusieurs modèles de Machine Learning 🆚

✅ Sélection et importance des features 🔍

✅ Optimisation des hyperparamètres 🎯


🚀 Contribuez et améliorez l'analyse du churn ! Toute suggestion ou amélioration est la bienvenue. 😊
