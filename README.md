# PYK — Bruxelles, 9 et 16 novembre 2026

Python pour le traitement des données — Redha Moulla.

## Support

[Support PDF (128 pages)](PYK_Bruxelles_9_et_16_novembre_2026.pdf)

## TP

1. [Introduction Python](01_Introduction_Python.ipynb)
2. [Analyse des données Churn](02_Analyse_Donnees_Churn.ipynb)
3. [German Credit](03_German_Credit.ipynb)
4. [Analyse des données SeLoger](04_Analyse_Donnees_Seloger.ipynb)

Versions Analyse Churn et German Credit limitées à la préparation, aux statistiques descriptives et à la visualisation. Les sections de modélisation et leurs sorties ont été retirées ; les autres cellules et sorties Drive sont conservées.

## Utilisation

Python 3.10 ou plus récent. Créer un environnement virtuel, puis :

```sh
pip install -r requirements.txt
jupyter lab
```

Dans Colab, importer le notebook puis le CSV correspondant. Les deux CSV sont à côté des notebooks pour conserver les chemins relatifs.

Le TP SeLoger utilise `selogerdata.csv` et les trois CSV du dossier `Seloger/`, à conserver à côté du notebook avec cette arborescence.
