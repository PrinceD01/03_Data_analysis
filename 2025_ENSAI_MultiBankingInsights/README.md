# Objectifs du projet
## Objectif principal
Analyser les comportements des clients multibancarisés de la banque fictive WeBank afin d’identifier les profils à risque de départ et de proposer des actions marketing concrètes pour renforcer leur fidélité.

## Intérêt pédagogique
- Mettre en pratique une démarche complète de data analyse et de data storytelling dans un contexte business.
- Apprendre à transformer des analyses data complexes en recommandations stratégiques compréhensibles par des décideurs non techniques.
- Travailler la visualisation de données à fort impact et l’articulation d’un discours orienté marketing et relation client.


# Structure du projet
```
project/
│
├── data/
│ ├── data_projet_dataviz_storytelling.csv # Données brutes
│
├── notebooks/
│ ├── Database exploration.ipynb # Nettoyage des données et exploration des variables
│
├── src/
│
├── outputs/ # Visualisations sauvegardées
│ ├── reports/ # Rapports restitués
│ ├── ├── Multi-banking analysis.pbix
│ ├── ├── Presentation of results.pptx
└─└── └── Summary of analysis method.pdf
```


# Jeu de données

**Source**: Données simulées fournies dans le cadre du projet académique.

**Caractéristiques principales:**
- Nombre d’observations : 64 373 clients.
- Nombre de variables : 37 variables clients couvrant : Profil sociodémographique, Comportement bancaire, Relation,client et satisfaction

**Variable cible :** flag_multibancarise (Indicateur de multibancarité)


# Méthodologie
1. **Nettoyage des données :**
- Exclusion des observations incohérentes (ex : clients mineurs, revenus négatifs).

2. **Préparation des variables :**
- Transformation et discretisation des variables pour faciliter l’analyse.

3. **Segmentation et sélection des variables :**
- Analyse des profils, des usages et de la relation client.
- Sélection des variables les plus pertinentes à partir de tests statistiques et d’une approche business.

4. **Structuration en 3 volets d’analyse :**
- Profiling : Identifier les segments de clients les plus exposés.
- Tracking des usages : Comprendre les comportements financiers et digitaux.
- Relation client : Mesurer la qualité perçue de la relation et les points de friction.

5. **Recommandations stratégiques :**
- Proposition d’actions concrètes orientées marketing et relation client.

6. **Construction d’un support de présentation impactant :**
- Storytelling visuel adapté à une direction métier, avec des graphiques, des KPI et des synthèses claires.
