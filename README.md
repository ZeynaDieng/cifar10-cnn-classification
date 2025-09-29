# Classification d’images CIFAR-10 avec CNN

Projet réalisé dans le cadre du cours de Deep Learning, Université Thomas Sankara.

## Objectif

Construire un CNN capable de classer les images du dataset **CIFAR-10** en 10 classes.

## Contenu du projet

* `cifar10_cnn1.ipynb` : notebook Jupyter contenant le code complet.
* `rapport.pdf` : rapport de projet.

## Étapes principales

1. Chargement et prétraitement des données CIFAR-10.
2. Construction d’un modèle CNN avec Keras.
3. Entraînement avec **data augmentation** et callbacks.
4. Évaluation du modèle :

   * Courbes loss et accuracy,
   * Matrice de confusion,
   * Exemples d’images correctement et incorrectement classées.

## Résultats

* Précision sur le test : \~80%
* Difficulté principale : confusion entre les classes similaires (chat/chien, voiture/camion).

## Installation et exécution

```bash
https://github.com/ZeynaDieng/cifar10-cnn-classification.git
cd cifar10-cnn-classification 
jupyter notebook cifar10_cnn1.ipynb
```

## Auteur

* **Seynabou Dieng**
  Université Thomas Sankara – Département d’Informatique
