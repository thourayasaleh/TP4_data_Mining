# TP4 Data Mining - Problème 9

## Sujet
Segmentation stratégique des clients avec le modèle RFM et l’algorithme K-Means.

## Objectif
L’objectif de ce projet est de transformer des données transactionnelles en informations utiles pour le marketing.

Nous utilisons le dataset Online Retail afin de segmenter les clients selon :
- Récence
- Fréquence
- Montant

## Membres du groupe
- Fatimetou Mohamed Lemine Saleh — C25248
- Sarra Abdel Aziz Rabany — C30911
- Maryeme Yahya Hourma — C29782

## Structure du projet

```text
TP4_DATA_MINING/
│
├── data/
│   ├── online_retail.csv
│   └── online_retail.parquet
│
├── notebooks/
│   └── solution_tp4_kmeans.ipynb
│
├── src/
│   └── test.py
│
├── README.md
└── requirements.txt

## Étapes réalisées

1. Chargement du dataset
2. Conversion CSV vers Parquet
3. Analyse des valeurs manquantes
4. Nettoyage des données
5. Création de la variable MontantTotal
6. Création du modèle RFM
7. Transformation logarithmique
8. Standardisation des données
9. Méthode du coude
10. Silhouette Score
11. Application de K-Means
12. Analyse des clusters
13. Profilage des clients
14. Stratégies marketing
15. Visualisation 2D des clusters
16. Visualisation 3D des clusters