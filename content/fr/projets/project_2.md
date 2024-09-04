---
title: "Système de Gestion des Indices de Prix"
date: 2024-08-10
draft: false
description: "Étude de Cas : Une application web interne développée avec Django pour gérer et mettre à jour les indices de prix des matériaux de construction dans le secteur des travaux publics."
cover:
    image: "images/project_2/se_connecter.png"  # Assurez-vous que le chemin est correct et que l'image existe dans le dossier spécifié
tags: ["Django", "Application Web", "Gestion des Indices de Prix", "Automatisation", "Chatbot"]
categories: ["Projets"]
---

## Aperçu

Le **Système de Gestion des Indices de Prix** a été développé durant mon stage d’un mois au DATRP du Ministère de l'Équipement et de l'Eau. Cette application web interne est conçue pour rationaliser la gestion et la mise à jour des indices de prix des matériaux de construction utilisés dans les travaux publics. Elle améliore l'efficacité opérationnelle en automatisant les tâches et en fournissant des outils avancés pour aider les responsables du DATRP.

## Problématique

Les responsables du DATRP rencontraient des difficultés dans la gestion et la mise à jour des indices de prix des matériaux de construction en raison d'un processus manuel et chronophage de création de canevas de valeurs à partir des fichiers Excel. Cela entraînait non seulement des inefficacités mais augmentait également le risque d'inexactitudes et d'erreurs dans les données, impactant la fiabilité des rapports de révision des prix et les processus de prise de décision.

## Étapes pour Résoudre le Problème

1. **Analyse des Besoins :** Réalisation d'une analyse détaillée du flux de travail existant pour comprendre les points de blocage et les besoins spécifiques des responsables du DATRP en matière de gestion des indices de prix.
  
2. **Conception et Développement :** Développement d'une application web centralisée utilisant Django, intégrant toutes les fonctionnalités nécessaires pour gérer les indices de prix, automatiser les tâches courantes et améliorer la précision des données.

3. **Automatisation de la Saisie de Données :** Mise en œuvre d'une interface d'importation Excel avec validation des données pour rationaliser la saisie, minimiser l'effort manuel et assurer la cohérence des données.

4. **Amélioration de l'Interaction Utilisateur :** Intégration d'un système d'authentification sécurisé avec contrôle d'accès basé sur les rôles pour protéger les informations sensibles et surveiller les activités des utilisateurs.

5. **Introduction d'Outils d'IA Avancés :** Développement d'un module expérimental de chatbot pour assister dans les requêtes de révision des prix et d'un prototype de détection de fraude, exploitant l'IA pour améliorer l'interaction utilisateur et l'intégrité des données.

6. **Tests et Itérations :** Réalisation de tests approfondis de l'application pour identifier et résoudre tout problème, suivis d'améliorations itératives basées sur les retours des responsables du DATRP.

## Objectifs

- **Rationaliser la Gestion des Indices de Prix :** Simplifier le processus de mise à jour et de gestion des indices de prix via une plateforme centralisée.
- **Automatiser les Tâches Répétitives :** Réduire la charge de travail manuel en automatisant les tâches de saisie et de validation de données.
- **Améliorer la Précision et la Sécurité des Données :** Mettre en place une authentification sécurisée des utilisateurs et une validation des données pour minimiser les erreurs et protéger les informations sensibles.
- **Exploiter les Fonctionnalités Avancées d'IA :** Utiliser des outils basés sur l'IA tels que des chatbots pour améliorer l'interaction utilisateur et faciliter l'apprentissage au sein de l'organisation.

## Fonctionnalités Clés

- **Système d'Authentification :** Connexion sécurisée et gestion des utilisateurs avec différents niveaux d'accès pour assurer la protection et le contrôle des données.
- **Tableau de Bord :** Affiche les derniers utilisateurs ayant accédé à l'application, améliorant les capacités de sécurité et de surveillance.
- **Interface d'Importation Excel :** Permet d'importer des fichiers Excel avec les indices de prix, incluant un système robuste de validation et d'aperçu des données pour garantir leur intégrité avant les mises à jour.
- **Vignettes d'Automatisation :** Propose un accès rapide aux tâches automatisées, y compris la création de canevas utilisés par la direction pour générer des rapports.
- **Fonctionnalités Expérimentales :**
  - **Chatbot pour les Révisions de Prix :** Un module expérimental utilisant un chatbot affiné avec l'ingénierie des prompts et RAG sur un corpus spécifique au DATRP, aidant dans les processus de révision des prix.
  - **Prototype de Détection de Fraude :** Utilise un modèle de classification ML pour identifier les anomalies potentielles et les entrées de données frauduleuses.

## Services Inclus

Ce projet intègre plusieurs services clés de mon portefeuille, notamment :

- **Automatisation des Données et Aide à la Décision :** Inclut des outils pour détecter les anomalies dans les données, visant à identifier de manière proactive les activités frauduleuses.
- **Intégration et Synchronisation des Données sur Mesure :** Se connecte en toute transparence avec les systèmes existants pour garantir une gestion synchronisée des données à travers les plateformes.
- **Formation et Développement Personnalisés des Employés :** Offre une formation personnalisée pilotée par l'IA basée sur les interactions des utilisateurs au sein de l'application.

## Technologies Utilisées

### Backend :
- **Python :**
  - **Django :** Framework pour construire le backend et gérer l'application web.
  - **Pandas :** Utilisé pour la manipulation des données et la gestion des opérations Excel.
  - **openpyxl :** Gère la lecture et l'écriture des fichiers Excel pour l'importation et l'exportation des données.
  - **OpenAI GPT-4 :** Alimente le chatbot, offrant des capacités conversationnelles avancées spécifiquement ajustées pour les sujets de révision des prix.
  - **Scikit-Learn :** Utilisé pour construire le modèle de classification pour la détection de fraude.

### Frontend :
- **HTML/CSS/JavaScript :** HTML, CSS et JS utilisés pour l'interface frontend, gardant l'expérience utilisateur simple et efficace.

## Galerie

Voici quelques captures d'écran montrant l'application en action :

![Tableau de Bord](/images/project_2/dashboard.png)
*Le tableau de bord principal montrant les indicateurs clés et les options de navigation.*

![Importation Excel](/images/project_2/importer.png)
*Interface d'importation des données Excel avec validation et aperçu des données.*

![Chatbot](/images/project_2/answer.png)
*Module de chatbot expérimental assistant dans les requêtes de révision des prix.*

![Gestion des Utilisateurs](/images/project_2/inscription.png)
*Gestion sécurisée des utilisateurs pour la gestion des différents niveaux d'accès.*

### Coût Total Estimé et Délai

Pour un package complet incluant toutes les fonctionnalités et services décrits, le coût total estimé varie de **1 250 $ à 2 700 $**, avec un délai de réalisation approximatif de **5 à 8 semaines**, incluant les révisions et les tests.

Voici une répartition détaillée des services inclus :

| Service                              | Tarif                   | Délai       | Révisions                                       |
|--------------------------------------|-------------------------|-------------|-------------------------------------------------|
| Automatisation des Données et Aide à la Décision | 600 $ - 1 200 $ par installation | 2-4 semaines | Jusqu'à 2 révisions pour les ajustements du modèle |
| Intégration et Synchronisation des Données | 100 $ - 300 $ par intégration | 1 semaine | Jusqu'à 2 révisions pour les ajustements mineurs |
| Formation Personnalisée et Développement | 500 $ - 1 200 $ par installation | 2-3 semaines | Inclut jusqu'à 2 révisions pour le contenu de la formation ou les ajustements du programme |
| **Hébergement et Maintenance**        | 50 $ - 150 $ par mois    | En continu  | Inclut les mises à jour de routine et le support |

Ces tarifs incluent tous les services et fonctionnalités nécessaires pour assurer un système entièrement fonctionnel et robuste adapté aux besoins du DATRP du Ministère de l'Équipement et de l'Eau.

## Contactez-moi

[Page de Contact](../../contact) — Contactez-moi pour plus d'informations ou pour planifier une démonstration.
