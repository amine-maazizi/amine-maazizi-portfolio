---
title: "Système de Gestion des Indices de Prix"
date: 2024-08-10
draft: false
description: "Une application web interne développée avec Django pour gérer et mettre à jour les indices de prix des matériaux de construction dans le secteur des travaux publics."
cover:
    image: "images/project_2/se_connecter.png"  # Assurez-vous que le chemin est correct et que l'image existe dans le dossier spécifié
tags: ["Django", "Application Web", "Gestion des Indices de Prix", "Automatisation", "Chatbot"]
categories: ["Projets"]
---

## Aperçu

Le **Système de Gestion des Indices de Prix** a été développé pendant mon stage d'un mois à la DATRP du Ministère de l'Équipement et de l'Eau. Cette application web interne est conçue pour simplifier la gestion et la mise à jour des indices de prix des matériaux de construction utilisés dans les travaux publics. Elle améliore l'efficacité opérationnelle en automatisant les tâches et en fournissant des outils avancés pour assister les fonctionnaires de la DATRP.

## Objectifs

- **Simplifier la Gestion des Indices de Prix** : Faciliter le processus de mise à jour et de gestion des indices de prix grâce à une plateforme centralisée.
- **Automatiser les Tâches Routinières** : Réduire la charge de travail manuelle en automatisant les tâches répétitives de saisie et de validation des données.
- **Améliorer la Précision et la Sécurité des Données** : Mettre en œuvre un système d'authentification sécurisé et une validation des données pour minimiser les erreurs et protéger les informations sensibles.
- **Exploiter les Fonctionnalités Avancées de l'IA** : Utiliser des outils basés sur l'IA tels que les chatbots pour améliorer l'interaction utilisateur et faciliter l'apprentissage au sein de l'organisation.

## Fonctionnalités Clés

- **Système d'Authentification** : Connexion sécurisée et gestion des utilisateurs avec différents niveaux d'accès pour garantir la protection et le contrôle des données.
- **Tableau de Bord** : Affiche les derniers utilisateurs qui ont accédé à l'application, renforçant les capacités de sécurité et de surveillance.
- **Interface d'Importation d'Excel** : Permet l'importation de fichiers Excel avec des indices de prix, inclut un système robuste de validation et de prévisualisation des données pour assurer leur intégrité avant les mises à jour.
- **Miniatures d'Automatisation** : Offrent un accès rapide aux tâches automatisées, y compris la création de canevas utilisés par la direction pour générer des rapports.
- **Fonctionnalités Expérimentales** :
  - **Chatbot pour la Révision des Prix** : Un module expérimental utilisant un chatbot affiné par l'ingénierie des prompts et RAG sur un corpus spécifique à la DATRP, facilitant les processus de révision des prix.
  - **Prototype de Détection de Fraude** : Utilise un modèle de classification ML pour identifier les anomalies potentielles et les entrées de données frauduleuses.

## Services Inclus

Ce projet intègre plusieurs services clés de mon portfolio, y compris :

- **Automatisation des Insights de Données et de la Prise de Décision** : Inclut des outils pour détecter les anomalies dans les données, visant à identifier de manière proactive les activités frauduleuses.
- **Intégration et Synchronisation des Données Personnalisées** : Se connecte de manière transparente aux systèmes existants pour assurer une gestion des données synchronisée à travers les plateformes.
- **Formation et Développement Personnalisés pour les Employés** : Offre une formation personnalisée basée sur l'IA en fonction des interactions des utilisateurs au sein de l'application.

## Technologies Utilisées

### Backend :
- **Python** :
  - **Django** : Framework pour construire le backend et gérer l'application web.
  - **Pandas** : Utilisé pour la manipulation des données et la gestion des opérations Excel.
  - **openpyxl** : Gère la lecture et l'écriture des fichiers Excel pour l'importation et l'exportation des données.
  - **OpenAI GPT-4** : Alimente le chatbot, offrant des capacités conversationnelles avancées spécifiquement ajustées pour les sujets de révision des prix.
  - **Scikit-Learn** : Utilisé pour construire le modèle de classification pour la détection de fraude.

### Frontend :
- **HTML/CSS/JavaScript** : HTML, CSS et JS simples pour l'interface frontend, assurant une expérience utilisateur simple et efficace.

## Galerie

Ci-dessous quelques captures d'écran illustrant l'application en action :

![Tableau de Bord](/images/project_2/dashboard.png)
*Le tableau de bord principal présentant les principales métriques et options de navigation.*

![Importation Excel](/images/project_2/importer.png)
*Interface d'importation de données Excel avec validation et prévisualisation des données.*

![Chatbot](/images/project_2/answer.png)
*Module expérimental de chatbot assistant pour les questions de révision des prix.*

![Gestion des Utilisateurs](/images/project_2/inscription.png)
*Gestion sécurisée des utilisateurs avec différents niveaux d'accès.*

### Coût Total Estimé et Délai de Réalisation

Pour un package complet incluant toutes les fonctionnalités et services décrits, le coût total estimé varie entre **1 250 $ et 2 700 $**, avec un délai de réalisation approximatif de **5 à 8 semaines**, incluant les révisions et les tests.

Voici une répartition détaillée des services inclus :

| Service                              | Tarification                | Délai        | Révisions                                        |
|--------------------------------------|-----------------------------|--------------|--------------------------------------------------|
| Automatisation des Insights de Données | 600 $ - 1 200 $ par configuration | 2-4 semaines | Jusqu'à 2 révisions pour ajustements du modèle   |
| Intégration et Synchronisation des Données | 100 $ - 300 $ par intégration | 1 semaine   | Jusqu'à 2 révisions pour des ajustements mineurs |
| Formation et Développement Personnalisés | 500 $ - 1 200 $ par configuration | 2-3 semaines | Inclut jusqu'à 2 révisions pour le contenu de la formation ou les ajustements du programme |
| **Hébergement et Maintenance**       | 50 $ - 150 $ par mois       | En continu   | Inclut les mises à jour de routine et le support |

Cette tarification inclut tous les services et fonctionnalités nécessaires pour garantir un système entièrement fonctionnel et robuste adapté aux besoins de la DATRP du Ministère de l'Équipement et de l'Eau.

## Contactez-moi

[Page de Contact](../../contact) — N'hésitez pas à me contacter pour plus d'informations ou pour planifier une démonstration.
