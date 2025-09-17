# Projet 8 -- Analyse prédictive pour l'investissement immobilier parisien

<div align="center">
<img src="https://images.unsplash.com/photo-1560518883-ce09059eeffa?w=800&h=300&fit=crop" alt="Paris Real Estate Analytics" />
</div>

## Contexte et objectif

**Client fictif :** Les Plus Beaux Logis de Paris\
**Objectif :** Développer un modèle d'analyse prédictive pour évaluer le
potentiel d'investissement immobilier à Paris.\
- Étudier l'évolution des prix au m² par arrondissement.\
- Identifier les zones d'opportunité post-COVID.\
- Fournir des estimations de valorisation fiables et rapides.

## Livrables du projet

    Paris-RealEstate-Analytics/
    ├── notebook_analyse.ipynb       # Analyse exploratoire et modélisation
    ├── presentation_resultats.pptx  # Restitution synthétique
    ├── data/                        # Données sources
    ├── README.md                    # Documentation projet

-   **Notebook d'analyse :** exploration des données, régression
    linéaire, clustering K-Means.\
-   **Présentation :** synthèse des tendances et recommandations.\
-   **Jeux de données :** transactions immobilières parisiennes
    nettoyées et prêtes à l'emploi.

## Méthodologie

1.  **Analyse exploratoire :** cartographie des prix, corrélations,
    détection d'outliers.\
2.  **Modélisation prédictive :** régression linéaire avec validation
    croisée (train/test).\
3.  **Segmentation :** classification K-Means pour regrouper les biens
    en segments cohérents.\
4.  **Restitution :** création de graphiques et présentation pour les
    décideurs.

## Points techniques

-   Python (Pandas, NumPy) pour la préparation et l'analyse des
    données.\
-   Scikit-learn pour la modélisation (régression, clustering).\
-   Visualisations avec Matplotlib/Seaborn.\
-   Validation des modèles avec R², RMSE et analyse des résidus.

## Résultats obtenus

-   Précision de prédiction supérieure à 85 % (R² ≈ 0.87).\
-   Segmentation automatique en 5 groupes de biens selon prix et
    surface.\
-   Réduction du temps d'analyse manuelle d'un bien de 4 heures à moins
    d'une heure.\
-   Identification de zones d'investissement prioritaires à fort
    potentiel.

---

<div align="center">
  <br/>
  <strong>Julien Liodenot</strong> • Business Intelligence Analyst
  © 2025 - Tous droits réservés
</div>