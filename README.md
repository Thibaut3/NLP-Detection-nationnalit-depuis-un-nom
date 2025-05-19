# Détection de Nationalité à partir de Noms (NLP)

Ce projet est un projet de traitement du langage naturel (NLP) qui vise à prédire la nationalité d'une personne à partir de son nom. Il est implémenté en utilisant PyTorch.

## Description du Projet

L'objectif principal de ce projet est de développer un modèle capable de classer un nom de famille et de prédire la nationalité d'origine. Le projet est structuré comme un notebook Jupyter et comprend les étapes suivantes :

1.  **Importation des bibliothèques :** Importation des bibliothèques nécessaires telles que torch, pandas, numpy, etc.
2.  **Chargement des données :** Chargement des données à partir de fichiers CSV.
3.  **Vectorisation des données :** Création d'un vocabulaire à partir des données et vectorisation des noms de famille.
4.  **Création du modèle :** Définition d'un modèle de réseau neuronal simple pour la classification.
5.  **Entraînement du modèle :** Entraînement du modèle sur les données d'entraînement.
6.  **Évaluation du modèle :** Évaluation des performances du modèle sur les données de test.
7.  **Prédiction de la nationalité :** Utilisation du modèle entraîné pour prédire la nationalité d'un nom de famille donné.

## Structure du Répertoire

Le projet est organisé comme suit :

* `NLP-Detection nationalité nom.ipynb` : Le notebook Jupyter contenant le code du projet.

## Installation

Pour exécuter ce projet, vous devez installer les bibliothèques suivantes :

* torch
* pandas
* numpy
* matplotlib
* tqdm

Vous pouvez installer ces bibliothèques en utilisant pip :

\`\`\`bash
pip install torch pandas numpy matplotlib tqdm
\`\`\`

## Utilisation

Pour utiliser ce projet, suivez les étapes suivantes :

1.  Clonez le dépôt :

    \`\`\`bash
    git clone https://github.com/Thibaut3/NLP-Detection-nationnalit-depuis-un-nom.git
    cd votre-repo
    \`\`\`

2.  Ouvrez le notebook `NLP-Detection nationalité nom.ipynb` dans Jupyter Notebook.

    \`\`\`bash
    jupyter notebook NLP-Detection nationalité nom.ipynb
    \`\`\`

3.  Exécutez les cellules du notebook pour charger les données, entraîner le modèle et prédire la nationalité d'un nom de famille.

## Exécution du modèle

Le notebook contient des exemples de code pour entraîner et évaluer le modèle. Pour exécuter le modèle :

1.  Importer les bibliothèques nécessaires.
2.  Charger les données d'entraînement et de test.
3.  Créer un vocabulaire à partir des données.
4.  Définir le modèle de classification.
5.  Entraîner le modèle sur les données d'entraînement.
6.  Évaluer le modèle sur les données de test.
7.  Utiliser le modèle entraîné pour prédire la nationalité d'un nom de famille.

## Prédiction de la nationalité

Le notebook contient une fonction `predict_nationality` qui prend en entrée un nom de famille et renvoie la nationalité prédite et sa probabilité. Par exemple :

\`\`\`python
predict_nationality("Wan", classifier, vectorizer)
\`\`\`

Cela renverra un dictionnaire contenant la nationalité prédite, la probabilité et le nom de famille.

## Résultats

Les résultats du modèle sont affichés dans le notebook. Ils comprennent la précision du modèle sur les données de test et des exemples de prédictions de nationalité pour des noms de famille donnés.
