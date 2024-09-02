---
title: "TrendViz : Tableau de bord analytique des meilleures ventes d'Amazon"
date: 2024-09-02
draft: false
description: "Un tableau de bord complet qui automatise l'extraction et l'analyse des données des meilleures ventes d'électronique sur Amazon, offrant des insights précieux grâce à des visualisations interactives et des rapports détaillés."
cover:
    image: "images/project_3/ratings.PNG"
tags: ["Analyse de Données", "Scraping Web", "Visualisation", "Python", "Flask", "Plotly"]
categories: ["Projets"]
---

## Aperçu

**TrendViz** est un tableau de bord analytique conçu pour extraire et analyser les données de la liste des meilleures ventes d'électronique d'Amazon. Ce projet automatise le scraping web, le nettoyage des données et les visualisations perspicaces, offrant aux utilisateurs un outil puissant pour explorer les tendances du marché et les préférences des consommateurs. Conçu avec un accent sur la précision, l'efficacité et l'interactivité, TrendViz transforme les données brutes en insights exploitables via une interface web conviviale.

## Objectifs

- **Extraire** : Automatiser l'extraction des données de la page des meilleures ventes d'électronique d'Amazon, capturant des informations clés sur les produits telles que le nom, le prix, les évaluations et le nombre de commentaires.
- **Nettoyer** : Traiter et nettoyer les données extraites pour assurer leur précision et cohérence pour une analyse significative.
- **Analyser** : Réaliser une analyse complète des attributs des produits pour identifier les tendances, les modèles et les corrélations.
- **Visualiser** : Présenter les insights des données à travers des visualisations interactives et informatives sur un tableau de bord web.
- **Rapporter** : Générer des rapports détaillés qui résument les principales conclusions et tendances, aidant les utilisateurs à prendre des décisions basées sur les données.

## Caractéristiques Principales

- **Scraping Web Automatisé** : Utilise Selenium et Beautiful Soup pour extraire des données de la page des meilleures ventes d'Amazon, y compris les noms des produits, les prix, les évaluations, les avis et les liens.
- **Identification des Meilleurs Produits** : Met en avant les produits les plus fréquents et les plus populaires parmi les meilleures ventes.
- **Analyse de la Plage de Prix** : Fournit un aperçu statistique des prix des produits, y compris les valeurs minimales, maximales, moyennes et médianes.
- **Insights sur les Évaluations et les Avis** : Analyse les évaluations moyennes, identifie les produits les mieux et les moins bien notés, et examine la distribution du nombre de commentaires.
- **Analyse de Corrélation** : Explore les relations entre le prix des produits, la popularité (avis) et les évaluations pour révéler des insights.
- **Visualisations Interactives** : Offre des graphiques et des diagrammes interactifs pour une exploration détaillée et engageante des tendances des données.
- **Interface Conviviale** : Propose un design propre et moderne avec une disposition intuitive qui améliore l'expérience utilisateur.
- **Scraping Web** : Extrait efficacement les données les plus récentes d'Amazon sans intervention manuelle, assurant que le tableau de bord reflète les dynamiques actuelles du marché.

## Workflow Détaillé

### 1. **Extraction des Données**
- Le système utilise Selenium pour la navigation automatisée et Beautiful Soup pour le parsing du HTML afin d'extraire les détails des produits tels que les noms, les prix, les évaluations et les liens de la page des meilleures ventes d'Amazon.

### 2. **Nettoyage des Données**
- Un script de nettoyage des données traite les données brutes en gérant les valeurs manquantes, en standardisant les formats, en supprimant les doublons et en convertissant les types de données pour une analyse précise.

### 3. **Analyse des Données**
- Analyse les métriques clés, y compris les meilleurs produits, les statistiques de la plage de prix, les évaluations moyennes et le nombre de commentaires.
- Corrèle divers points de données, tels que prix vs popularité et évaluations vs nombre de commentaires, pour révéler des insights.

### 4. **Visualisation des Données**
- Utilise Plotly.js pour créer des diagrammes de dispersion interactifs, des histogrammes et d'autres éléments visuels permettant aux utilisateurs d'explorer les tendances des données directement depuis le tableau de bord.

### 5. **Rapports du Tableau de Bord**
- Affiche les conclusions sur un tableau de bord web basé sur Flask avec des sections dédiées à chaque aspect de l'analyse, tels que les meilleurs produits, les statistiques de prix et les insights de corrélation.
- Le tableau de bord est conçu pour être facile à utiliser, permettant aux utilisateurs de naviguer dans les différentes sections et d'interagir avec les visualisations de données.

### 6. **Interaction Utilisateur**
- Les utilisateurs peuvent explorer différentes sections du tableau de bord pour voir les insights et les tendances, avec des fonctionnalités leur permettant d'approfondir les points de données spécifiques pour une analyse plus poussée.

## Technologies Utilisées

### Backend:
- **Python**:
  - **Selenium & Beautiful Soup** : Pour le scraping web pour collecter des données d'Amazon.
  - **Pandas** : Gère le traitement, le nettoyage et l'analyse des données.
  - **Flask** : Alimente l'application web, servant le tableau de bord et gérant la logique backend.
  - **Jinja2** : Moteur de templates pour rendre HTML dynamiquement en fonction des résultats d'analyse de données.

### Frontend:
- **Plotly.js** : Utilisé pour créer des visualisations de données interactives au sein du tableau de bord.
- **HTML/CSS/JavaScript** : Utilise HTML, CSS et JavaScript pour créer une interface réactive et conviviale.

## Galerie

Voici quelques captures d'écran montrant l'application en action :

![Top produits](/images/project_3/top.PNG)
*Le tableau de bord principal présentant les articles les plus vendus.*

![Statistiques](/images/project_3/stats.PNG)
*Affiche les statistiques clés extraites des données scrappées.*

![Graphique des prix](/images/project_3/pricings.png)
*Graphique montrant la corrélation entre les prix et les évaluations.*

![Données](/images/project_3/data.png)
*Fichier CSV des données scrappées.*

## Estimations de Prix et de Temps

Pour un package complet incluant toutes les fonctionnalités et services décrits, le coût total estimé varie de **$925 à $2,000**, avec un délai de réalisation approximatif de **5 à 8 semaines**, y compris les révisions et les tests.

| Service                              | Tarification              | Délai       | Révisions                                      |
|--------------------------------------|---------------------------|-------------|------------------------------------------------|
| **Automatisation des Insights de Données**         | $600 - $1200 par configuration   | 2-4 semaines   | Jusqu'à 2 révisions pour ajustements de modèle        |
| **Génération de Rapports**                | $75 - $200 par configuration     | 1 semaine      | Comprend jusqu'à 2 révisions pour ajustements des données|
| **Scraping Web**                     | $150 - $300 par configuration    | 1-2 semaines   | Jusqu'à 2 révisions pour les paramètres d'extraction    |
| **Intégration et Synchronisation des Données** | $100 - $300 par intégration | 1 semaine | Jusqu'à 2 révisions pour ajustements mineurs       |
| **Personnalisation et Support**        | $50 - $100 par mois     | Continu     | Couvre les mises à jour de routine et les améliorations mineures |

## Contactez-moi

[Page de Contact](../../contact) — Contactez-moi pour plus d'informations ou pour planifier une démonstration.
