# TP4 Data Mining — Segmentation Stratégique des Clients (RFM & K-Means)

## 📚 Contexte

Ce projet a été réalisé dans le cadre du module **Data Mining**.

L’objectif est d’analyser des données transactionnelles réelles afin de segmenter les clients selon leurs comportements d’achat grâce au modèle **RFM** et à l’algorithme **K-Means**.

Le dataset utilisé est **Online Retail Dataset**, contenant des transactions d’un site e-commerce basé au Royaume-Uni.

---

# 🎯 Objectifs du projet

Ce projet vise à :

- Nettoyer et préparer les données
- Transformer les données transactionnelles
- Construire le modèle RFM
- Appliquer l’algorithme K-Means
- Identifier différents profils de clients
- Visualiser les clusters en 2D et 3D
- Proposer des stratégies marketing adaptées

---

# 👥 Membres du groupe

| Nom | Matricule |
|---|---|
| Fatimetou Mohamed Lemine Saleh | C25248 |
| Sarra Abdel Aziz Rabany | C30911 |
| Maryeme Yahya Hourma | C29782 |

---

# 🗂️ Structure du projet

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
```

---

# ⚙️ Technologies utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 📌 Étapes réalisées

## Phase 1 — Acquisition et Ingestion

- Chargement du dataset
- Conversion CSV → Parquet
- Comparaison des performances

## Phase 2 — Data Cleaning

- Analyse des valeurs manquantes
- Suppression des lignes sans `CustomerID`
- Nettoyage des données aberrantes

## Phase 3 — Feature Engineering

- Création de la variable `MontantTotal`
- Construction du modèle RFM
- Transformation logarithmique
- Standardisation des données

## Phase 4 — Clustering

- Méthode du coude (Elbow Method)
- Silhouette Score
- Application de K-Means
- Création des clusters

## Phase 5 — Data Storytelling

- Analyse des clusters
- Profilage des clients
- Stratégies marketing
- Visualisation 2D
- Visualisation 3D

---

# 📊 Résultats obtenus

Le modèle K-Means a permis de segmenter les clients en plusieurs groupes selon :

- La récence des achats
- La fréquence des commandes
- Le montant total dépensé

Les visualisations 2D et 3D montrent clairement la séparation des différents profils clients.

---

# 🎥 Vidéos Loom

## 👩‍💻 Partie 1 — Présentation et Data Cleaning (C25248)
https://www.loom.com/share/c2a25185c8c64fe3bd37ee50d266dc37

## 👩‍💻 Partie 2 — Modèle RFM et Clustering (C30911)
https://www.loom.com/share/626c00d64d1345ac8410cc2aa1f6ee4a

## 👩‍💻 Partie 3 — Visualisations et Conclusions (C29782)
https://www.loom.com/share/ac936103940c4d56b5109fa609fe8cf1

---

# 🚀 Exécution du projet

Installer les dépendances :

```bash
pip install -r requirements.txt
```

Lancer Jupyter Notebook :

```bash
jupyter notebook
```

---

# ✅ Conclusion

Ce projet nous a permis de découvrir une pipeline complète de Data Mining :

- Préparation des données
- Transformation RFM
- Clustering avec K-Means
- Analyse comportementale des clients

Cette approche aide les entreprises à mieux comprendre leurs clients et à améliorer leurs stratégies marketing.

---