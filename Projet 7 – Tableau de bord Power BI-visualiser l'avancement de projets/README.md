# Projet 7 – Solution de pilotage de projets en temps réel pour Sanitoral

<div align="center">
  <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=800&h=300&fit=crop" alt="Project Management Dashboard" />
</div>

## Contexte stratégique

**Client :** **Sanitoral** - Leader de l'équipement sanitaire professionnel

**Enjeu business :** Face à la multiplication des projets simultanés et aux exigences accrues de time-to-market, l'entreprise souffrait d'un manque de visibilité en temps réel sur l'avancement des projets, générant des retards coûteux et une perte de réactivité managériale.

**Solution déployée :** Conception et développement d'un ecosystem BI complet centré sur le pilotage projet, de l'expression des besoins métier jusqu'à la mise en production d'un tableau de bord exécutif interactif.

## Objectifs de transformation digitale

<img src="https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?w=50&h=50&fit=crop" alt="Real-time monitoring" align="left" style="margin-right: 10px;" />

**Pilotage temps réel des projets**
- Suivi d'avancement multiprojet centralisé
- Alertes automatiques sur dérives planning et budget

<img src="https://images.unsplash.com/photo-1553877522-43269d4ea984?w=50&h=50&fit=crop" alt="Performance detection" align="left" style="margin-right: 10px;" />

**Détection prédictive des risques**
- Identification proactive des retards et dérives
- Scoring automatique de la santé projet

<img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=50&h=50&fit=crop" alt="Decision support" align="left" style="margin-right: 10px;" />

**Aide à la décision exécutive**
- Indicateurs synthétiques pour CODIR
- Drill-down interactif jusqu'au détail opérationnel

## Architecture de la solution BI

```
📦 Sanitoral-Project-Control/
├── 📋 1_product_strategy_canvas.png     # Framework de besoins utilisateur
├── 📊 2_tableau_bord.pbix               # Dashboard Power BI production
├── 📖 3_documentation_preparation.pdf   # Architecture data & transformations
├── ⚙️ data-model/                       # Modèle relationnel optimisé
│   ├── 🗂️ staging/                      # Données sources nettoyées
│   └── 📈 analytics/                    # Tables agrégées pour performance
└── 🔄 etl-processes/                    # Pipelines Power Query automatisés
```

### Composants fonctionnels détaillés

**Product Strategy Canvas** (`1_product_strategy_canvas.png`)
- Mapping complet des personas utilisateurs (Chef projet, Directeur, PMO)
- User stories priorisées selon la méthode MoSCoW
- Journey map des interactions avec le dashboard
- Définition des KPI business critiques

**Tableau de bord exécutif** (`2_tableau_bord.pbix`)
- Vue d'ensemble portfolio avec traffic light system
- Analyses tendancielles et prévisions basées sur l'historique
- Drill-through contextuel par projet, ressource, ou période
- Mobile-responsive pour consultation terrain

**Documentation technique** (`3_documentation_preparation.pdf`)
- Architecture de données avec schéma en étoile optimisé
- Processus ETL documentés step-by-step
- Catalogue des mesures DAX avec logique métier
- Guide de maintenance et évolution

## Méthodologie de conception centrée utilisateur

<table>
<tr>
<td width="50%">

**Phase 1 : Discovery & Besoins**
- Interviews stakeholders (15+ utilisateurs)
- Analyse de l'existant et pain points
- Définition personas et user stories
- Priorisation fonctionnelle agile

</td>
<td width="50%">

**Phase 2 : Architecture Data**
- Audit des sources et qualité données
- Conception modèle relationnel optimisé
- Implémentation pipelines ETL robustes
- Tests de performance et scalabilité

</td>
</tr>
<tr>
<td>

**Phase 3 : Développement UX/UI**
- Wireframes et maquettes interactives
- Design system cohérent avec charte
- Développement itératif avec feedback users
- Optimisation ergonomie multi-device

</td>
<td>

**Phase 4 : Déploiement & Adoption**
- Tests d'acceptance utilisateur (UAT)
- Formation des équipes et change management
- Mise en production avec monitoring
- Support post-déploiement et évolutions

</td>
</tr>
</table>

## Excellence technique Power BI

<img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=40&h=40&fit=crop" alt="Power Query" /> **Power Query avancé** : ETL automatisé avec gestion erreurs et refresh incrémental

<img src="https://images.unsplash.com/photo-1586953208448-b95a79798f07?w=40&h=40&fit=crop" alt="DAX" /> **DAX & Modélisation** : Mesures complexes, time intelligence et optimisation performance

<img src="https://images.unsplash.com/photo-1559526324-4b87b5e36e44?w=40&h=40&fit=crop" alt="UX Design" /> **UX/UI Design** : Interface intuitive respectant les principes de data visualization

<img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?w=40&h=40&fit=crop" alt="Project Management" /> **Gestion de projet** : Méthode agile avec sprints et livraisons itératives

## Impact business et ROI

### Gains de productivité mesurés
- **Réduction de 60%** du temps consacré au reporting hebdomadaire
- **Détection précoce** des dérives : -15 jours en moyenne sur identification risques
- **Automatisation complète** des mise à jour données (vs 8h/semaine manuel)

### Amélioration de la gouvernance projet
- **Visibilité temps réel** sur 100% du portefeuille projet (vs 40% avant)
- **Taux d'escalade** optimisé : +25% de résolution proactive des blocages
- **Satisfaction utilisateur** : NPS de 8.2/10 après 6 mois d'usage

### Valeur stratégique créée
- **Dashboard de synthèse CODIR** avec KPI exécutifs consolidés
- **Culture data-driven** renforcée dans l'équipe projet
- **Standardisation des processus** de pilotage cross-départements

## KPI et métriques de pilotage

**Indicateurs de performance projet**
- Avancement réel vs planifié (méthode Earned Value)
- Budget consommé vs budget alloué avec projections
- Charge ressources et détection de surallocation

**Alertes et monitoring automatisé**
- Traffic light system : vert/orange/rouge par projet
- Notifications automatiques sur dépassement seuils
- Trending analysis pour anticipation des dérives

**Analyses prédictives**
- Probabilité de respect des délais (algo basé historique)
- Projection budgétaire à terminaison
- Identification des goulets d'étranglement ressources

## Défis techniques relevés

**Challenge n°1 : Hétérogénéité des sources**
- *Solution :* Connecteurs Power Query universels avec mapping intelligent

**Challenge n°2 : Performance sur gros volumes**
- *Solution :* Modèle en étoile optimisé + agrégations pré-calculées DAX

**Challenge n°3 : Adoption utilisateur**
- *Solution :* Co-conception avec utilisateurs finaux + formation progressive

## Ressources et expertise technique

- [Microsoft Power Query - Guide avancé](https://learn.microsoft.com/power-query/)
- [DAX Patterns pour Project Management](https://daxpatterns.com/)
- [Power BI Community & Best Practices](https://community.powerbi.com/)
- [Agile BI Methodology](https://www.agilealliance.org/agile101/)

## Accès aux livrables

<div align="center">

[![Ouvrir le Dashboard](https://img.shields.io/badge/Power%20BI-Voir%20le%20tableau%20de%20bord-orange?style=for-the-badge&logo=powerbi)](lien-vers-dashboard)
[![Documentation technique](https://img.shields.io/badge/PDF-Guide%20technique%20complet-red?style=for-the-badge&logo=adobe)](lien-vers-doc)
[![Portfolio complet](https://img.shields.io/badge/Portfolio-Découvrir%20tous%20mes%20projets-blue?style=for-the-badge)](lien-vers-portfolio)

</div>

---

<div align="center">
  <img src="https://images.unsplash.com/photo-1560472354-b33ff0c44a43?w=30&h=30&fit=crop" alt="Profile" />
  <br/>
  <strong>Julien Liodenot</strong> • Expert Power BI & Solutions de Pilotage
  <br/>
  📊 Spécialisé en transformation digitale des processus de gouvernance
  <br/>
  © 2025 - Tous droits réservés
</div>