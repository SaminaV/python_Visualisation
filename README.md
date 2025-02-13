# Analyse et Visualisation des Ventes et Performances des Produits

## Objectif

L'objectif principal de ce projet est d'explorer, analyser et visualiser un jeu de données pour identifier des tendances clés, comprendre les comportements des clients et proposer des recommandations stratégiques basées sur des insights exploitables.

## Méthodologie

### 1. Préparation des Données
Le jeu de données comprend **676 lignes**, nettoyés et préparés pour l'analyse. Les colonnes clés incluent :
- **Nom du produit**
- **Prix**
- **Coût de livraison**
- **Poids des produits**
- **Scores des produits**
- **Prix des concurrents**

### 2. Exploration et Visualisation
Des visualisations variées ont été utilisées pour explorer les relations entre les variables. Une attention particulière a été accordée aux **comparaisons avec les concurrents**, permettant de situer l’entreprise étudiée dans son contexte concurrentiel.

## Résultats Clés et Visualisations

### 1. Distribution du Prix Total
La majorité des transactions se situent dans une fourchette de prix bas à modéré, indiquant une prépondérance de produits abordables. Les produits de prix moyen sont les plus populaires auprès des clients.

### 2. Tendance des Ventes dans le Temps
Une **croissance continue des ventes** a été observée au fil des mois, cependant, depuis **mai 2018**, une tendance à la baisse a été remarquée. Cette diminution pourrait être liée à divers facteurs tels que des changements saisonniers, des ajustements dans les stratégies marketing, ou encore une saturation du marché.  
**Action :** Il est essentiel de mener une analyse plus approfondie pour identifier les causes sous-jacentes de cette baisse et ajuster les stratégies pour inverser cette tendance.


![Capture d’écran 2025-01-03 à 15 36 09](https://github.com/user-attachments/assets/7b6541af-bddd-457c-9da6-f88448f0337f)


### 3. Tendances des Prix par Rapport aux Concurrents
Une analyse comparative montre que **Compétiteur 1 (violet)** maintient les prix les plus bas, potentiellement pour attirer des clients sensibles au prix.  

![Capture d’écran 2025-01-03 à 17 46 23](https://github.com/user-attachments/assets/1d59c643-b233-47b3-80e0-2e48a7015d1a)


### 4. Analyse des Jours de Vente
Contrairement aux attentes, les **ventes en semaine** surpassent celles du week-end. En effet, **71,5% des ventes** se produisent en semaine, tandis que seulement **28,5% ont lieu le week-end**. Cela représente une opportunité souvent négligée.  
**Proposition :** Lancer des promotions ou offres spéciales le week-end pour équilibrer la répartition des ventes et potentiellement augmenter les ventes pendant cette période.


### 5. Produits les Plus Vendus et Générateurs de Revenus
Les produits les plus vendus ne sont pas nécessairement les plus rentables. Par exemple, **'furniture2'**, malgré ses volumes élevés, génère moins de revenus que **'health2'**, vendu en quantités moindres mais avec un prix unitaire élevé.  
**Stratégie :** Augmenter la visibilité des produits à forte marge et optimiser les stocks pour maximiser les revenus.

![Capture d’écran 2025-01-03 à 15 38 59](https://github.com/user-attachments/assets/b49f3353-01db-4b83-81ee-ebdd50c579d2)




## Prochaines Étapes : Aller Plus Loin

### 1. Automatisation des Rapports et Tableaux de Bord
Créer des **tableaux de bord interactifs** avec des outils comme Power BI, Tableau ou Python (Dash, Streamlit) pour permettre un suivi en temps réel des indicateurs clés (ventes, marges, performances produits).

### 2. Segmentation Avancée des Clients
Utiliser des techniques de segmentation pour identifier des groupes spécifiques de clients, par exemple :
- Les **clients réguliers vs. occasionnels**
- Les **gros acheteurs vs. ceux à petit budget**

Une segmentation efficace permet de personnaliser les campagnes marketing, d’augmenter les conversions et de maximiser la fidélisation client.

### 3. Analyse Prédictive avec Machine Learning
Mettre en œuvre des algorithmes de **machine learning** pour :
- Prédire les **ventes futures** en fonction des saisons, des tendances ou des campagnes passées.
- Anticiper les **ruptures de stock** ou les pics de demande.

### 4. Système de Recommandations Personnalisées
Déployer un moteur de **recommandations** basé sur les données d'achat précédentes, en utilisant des techniques de filtrage collaboratif ou de clustering.  
Cela permet d'augmenter les **ventes croisées** (cross-sell) et d'inciter les clients à acheter davantage en leur proposant des produits pertinents.

### 5. Scoring des Produits et Clients
Scorer les clients pour identifier par exemple Les clients VIP ou les clients à risque de désengagement.
Cela permet de concentrer les efforts sur les clients et produits qui rapportent le plus à l’entreprise.

