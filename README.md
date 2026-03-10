# Prédiction des Maladies Cardiovasculaires

## 📋 Objectif

Ce projet utilise le **Machine Learning** pour prédire la présence de maladies cardiovasculaires basé sur les données de santé des patients.

## 📊 Dataset

- **Fichier** : `cardio_data_processed.csv`
- **Nombre d'enregistrements** : + 70 000 patients
- **Variables** : Âge, sexe, poids, taille, tension artérielle, cholestérol, glucose, mode de vie, etc.
- **Cible** : Présence ou absence de maladie cardiovasculaire (0 = Non, 1 = Oui)

## 🧠 Modèle

- **Algorithme** : Régression Logistique
- **Approche** : Classification binaire supervisée
- **Prétraitement** :
  - Calcul de l'âge en années
  - Calcul du BMI
  - Catégorisation de la tension artérielle
  - Encodage des variables catégoriques

## 📈 Résultats

Le modèle effectue les prédictions sur l'ensemble de test :

- Environ **17 197** cas prédits comme malades
- Environ **22 299** cas prédits comme sains

## 🛠️ Technologies

- **Python**
- **pandas** : Manipulation des données
- **scikit-learn** : Machine Learning
- **matplotlib & seaborn** : Visualisation

## 🚀 Comment utiliser

1. Téléchargez le repository
2. Installez les dépendances : `pip install pandas scikit-learn matplotlib seaborn numpy`
3. Ouvrez le notebook : `python.ipynb`
4. Exécutez les cellules pour voir l'analyse complète et les prédictions

## 📁 Structure du projet

```
cardio-ml-prediction/
├── python.ipynb                    # Notebook complet avec analyse et modèle
├── cardio_data_processed.csv       # Dataset
└── README.md                       # Ce fichier
```

## 💡 Améliorations futures

- Tester d'autres algorithmes (Random Forest, SVM, Réseau de neurones)
- Optimiser les hyperparamètres
- Gérer le déséquilibre des classes
- Ajouter la validation croisée

## 👤 Auteur

Amin ABDULLAHI ABDI - Analyse Data Junior et Journaliste
