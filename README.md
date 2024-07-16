# 💶 Identification Automatique de Faux Billets pour l’ONCFM

Bienvenue dans le repository du projet **Identification Automatique de Faux Billets pour l’ONCFM**. Ce projet vise à mettre en place une modélisation capable d’identifier automatiquement les vrais et faux billets en euros à partir de certaines dimensions du billet et des éléments qui le composent.

## 📚 Contexte du Projet

Vous êtes consultant Data Analyst dans une entreprise spécialisée dans la data. Votre entreprise a décroché une prestation en régie au sein de l’Organisation nationale de lutte contre le faux-monnayage (ONCFM). Cette institution a pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros.

## 🎯 Objectifs du Projet

1. Nettoyer et analyser les données fournies.
2. Explorer différentes pistes pour la construction de l’algorithme de détection.
3. Mettre en place et tester divers modèles de classification.
4. Retenir le modèle le plus performant pour l’application finale de prédiction.

## 📦 Livrables

1. **Notebook Python** : Contenant l’ensemble des traitements et des tests effectués.
2. **Application Finale** : Modèle final de prédiction des faux billets.

## 📂 Structure du Repository
```
├── Moreno_Bastien_1_code_082023.ipynb                          # Nettoyage et analyse exploratoire des données
├── Moreno_Bastien_2_application_finale_082023.ipynb            # Application de prédiction
├── billets.csv                                                 # Dataset du projet
├── billets_predictions_KMeans.csv                              # Prédictions avec KMeans
├── billets_predictions_Regression_Logistique.csv               # Prédictions avec Régression Logistique
├── id_Kmeans.pickle                                            # Dictionnaire d'identification des clusters
├── modele_Kmeans.pickle                                        # Modèle KMeans
├── modele_RegLog.pickle                                        # Modèle de régression logistique
├── selection.pickle                                            # Sélection des variables
├── README.md                                                   # Ce fichier
```

## 🧑‍💻 Utilisation

### Nettoyage et Analyse Exploratoire
Le Notebook `Moreno_Bastien_1_code_082023.ipynb` contient le code pour le nettoyage et l’analyse exploratoire des données. Ouvrez ce fichier pour voir les étapes de préparation des données avant leur modélisation.

### Application de Prédiction
Le Notebook `Moreno_Bastien_2_application_finale_082023.ipynb` contient le code de l'application finale de prédiction. Utilisez ce fichier pour voir comment le modèle final est mis en place et comment il peut être utilisé pour prédire les faux billets.

## 📊 Détails des Modèles

- **KMeans Clustering** : Modèle KMeans utilisé pour identifier les clusters dans les données.
- **Régression Logistique** : Modèle de régression logistique utilisé pour prédire les faux billets.
- **Sélection des Variables** : Processus de sélection des variables les plus importantes pour la modélisation.

## 👨‍💻 Auteur
Bastien Moreno - Data Scientist passionné par l'analyse de données et le développement de modèles intelligents.\
Pour en savoir plus sur moi et mes projets, n'hésitez pas à me contacter via mon [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bastien-moreno441237/).