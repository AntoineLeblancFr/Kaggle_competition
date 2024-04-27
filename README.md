# INF8245E COMPETITION - FALL 2023

**Team:** Lequip2.

**Students:** Antoine Leblanc, Maxime Montois, Hugo Petrilli.

Ce code présente notre travail pour la compétition Kaggle inf8245e-f2023. Il présente les différentes étapes réalisées tout au long de ce projet et l'aboutissement de la solution finale publiée sur Kaggle.

Ce dossier contient le notebook `final.ipynb` ainsi que le fichier final `result.csv` deposé sur Kaggle.

## Setup

Avant d'exécuter le code, vérifiez que le lien vers le dossier contenant les données est correct dans la section `setup` du notebook `final.ipynb`.

Par défaut, la cellule `setup` contient le code pour connecter le notebook à Google Drive. Cependant, ces cellules sont optionnelles. Il suffit simplement de définir correctement la variable `root_path`, qui correspond au dossier dans lequel est enregistré le dossier `data` contenant les fichiers de données.

Exemple d'architecture de dossier :

```
root-path/
│
├── data/
│   ├── train_features.csv
│   ├── train_labels.csv
│   └── test_features.csv 
│
└── final.ipynb
```

## Exportation de  la solution.

La dernière cellule contient le code pour exporter le vecteur `y_test` dans un fichier `csv`. La variable `path` doit être modifiée afin de spécifier le chemin d'enregistrement du dossier.