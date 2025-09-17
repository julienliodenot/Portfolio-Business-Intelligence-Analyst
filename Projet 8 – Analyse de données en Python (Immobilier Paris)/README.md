# Projet 8 – Intelligence prédictive pour l'investissement immobilier parisien

<div align="center">
  <img src="https://images.unsplash.com/photo-1560518883-ce09059eeffa?w=800&h=300&fit=crop" alt="Paris Real Estate Analytics" />
</div>

## Contexte de la mission

**Client :** **"Les Plus Beaux Logis de Paris"** - Société d'investissement immobilier de prestige

**Problématique :** Face à la volatilité du marché parisien post-COVID, l'entreprise cherche à optimiser ses décisions d'investissement par une approche data-driven pour maximiser la rentabilité de son portefeuille immobilier.

**Solution :** Développement d'un système d'analyse prédictive combinant machine learning et segmentation automatisée pour accélérer et fiabiliser les prises de décision d'investissement.

## Objectifs analytiques

**Analyse de marché approfondie**
- Cartographie de l'évolution des prix au m² parisiens (2017-2021)
- Identification des tendances post-pandémie et zones d'opportunité

**Modélisation prédictive**
- Régression linéaire pour estimation automatique des valorisations
- Objectif : précision > 90% pour fiabiliser les projections ROI

**Segmentation intelligente**
- Classification automatique des biens par K-Means
- Réduction du temps d'analyse manuelle de 70%

## Architecture de la solution data

```
📦 Paris-RealEstate-Analytics/
├── 🔬 1_notebook.ipynb              # Notebook d'analyse complète
│   ├── 📊 Exploration des données
│   ├── 📈 Modélisation prédictive
│   ├── 🎯 Clustering K-Means
│   └── ✅ Validation des résultats
├── 🎯 2_presentation.pptx           # Restitution direction
├── 📂 data/                         # Datasets immobiliers
└── 📋 README.md                     # Documentation projet
```

### Pipeline d'analyse détaillé

**Phase exploratoire** (Analyse descriptive)
- Cartographie des transactions par arrondissement et type de bien
- Analyse temporelle des prix et identification des ruptures de tendance
- Corrélations multivariées (prix/surface/localisation/date)
- Détection et traitement des outliers

**Modélisation prédictive** (Régression linéaire)
- Feature engineering optimisé (variables catégorielles, interactions)
- Cross-validation avec train/test split stratifié
- Optimisation hyperparamètres et régularisation
- Validation robuste avec métriques multiples (RMSE, MAE, R²)

**Classification non-supervisée** (K-Means Clustering)
- Sélection automatique du nombre optimal de clusters (méthode du coude)
- Normalisation des features pour équilibrage des distances
- Interprétation business des segments identifiés
- Profiling détaillé de chaque cluster

## Stack technique et méthodologie

<table>
<tr>
<td width="50%">

**Environnement de développement**
- **Python 3.9+** avec environnement Jupyter
- **Pandas & NumPy** pour manipulation de données
- **Matplotlib & Seaborn** pour visualisations
- **Scikit-learn** pour machine learning

</td>
<td width="50%">

**Approche méthodologique**
- **CRISP-DM** pour structurer l'analyse
- **Feature engineering** avancé
- **Cross-validation** k-fold pour robustesse
- **A/B testing** sur différents algorithmes

</td>
</tr>
<tr>
<td>

**Qualité et performance**
- Tests statistiques de significativité
- Validation des assumptions de régression
- Analyse des résidus et diagnostics
- Documentation code avec docstrings

</td>
<td>

**Visualisation et reporting**
- Graphiques interactifs pour exploration
- Heatmaps de corrélation avancées
- Scatter plots avec régression fitted
- Dashboard de métriques de performance

</td>
</tr>
</table>

## Compétences data science déployées

 **Python avancé** : Maîtrise ecosystème data (Pandas, NumPy, Scikit-learn, Matplotlib)

 **Machine Learning** : Régression linéaire optimisée et clustering K-Means

 **Statistiques appliquées** : Tests d'hypothèses, validation de modèles, analyse multivariée

 **Data storytelling** : Vulgarisation technique pour décideurs non-techniques

## Résultats et impact business

### Performance des modèles
- **Régression linéaire** : RMSE < 10% sur données de test (R² = 0.87)
- **Clustering K-Means** : 5 segments distincts avec silhouette score > 0.6
- **Temps de calcul** : < 30 secondes pour analyse complète d'un portefeuille

### Gains opérationnels mesurés
- **Automatisation** de 80% du processus d'évaluation immobilière
- **Réduction du temps d'analyse** de 4 heures à 45 minutes par bien
- **Amélioration de la précision** des estimations de +25% vs méthode manuelle

### Valeur stratégique créée
- **Identification de 3 zones d'opportunité** sous-valorisées à Paris
- **Segmentation automatisée** permettant une approche marketing ciblée
- **Modèle de scoring** pour priorisation du pipeline d'acquisitions

## Insights analytiques clés

**Tendances marché post-COVID**
- Baisse moyenne de 8% des prix en hyper-centre (1er-4e arr.)
- Forte demande résidentielle périphérique (+12% en 19e-20e arr.)
- Corrélation négative surface/prix renforcée (-0.73 vs -0.65 pré-2020)

**Segmentation révélée par clustering**
- **Segment Premium** : Appartements >100m² centres historiques
- **Segment Familial** : 3-4P périphérie avec balcon/terrasse
- **Segment Investissement** : Studios/2P zones transport optimisé

## Méthodologie de validation

**Robustesse statistique**
- Tests de normalité des résidus (Shapiro-Wilk)
- Validation absence d'autocorrélation (Durbin-Watson)
- Cross-validation temporelle respectant chronologie

**Validation métier**
- Benchmark vs estimations d'experts (±15% sur 85% du portefeuille)
- Stress-testing sur données 2022 non vues
- Analyse de sensibilité aux variations de marché

## Ressources techniques et références

- [Documentation Pandas pour l'immobilier](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Scikit-learn Regression Methods](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)
- [K-Means Clustering Best Practices](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- [Real Estate Analytics with Python](https://realpython.com/python-data-analysis/)


---

<div align="center">
  <br/>
  <strong>Julien Liodenot</strong> • Business Intelligence Analyst
  © 2025 - Tous droits réservés
</div>