# Sports Performance App

Plateforme full-stack de prédiction de risques sportifs basée sur le machine learning, conçue pour aider les clubs professionnels et les préparateurs physiques à anticiper les risques liés à la charge d'entraînement.

## Objectif

Fournir un outil capable de centraliser les données de suivi des athlètes (charge d'entraînement, historique, indicateurs physiologiques) et d'en tirer des indicateurs de risque exploitables, via un modèle d'apprentissage automatique entraîné sur ces données.

## Architecture

- **Backend** : API REST développée avec FastAPI (Python), exposant les endpoints de gestion des données et de prédiction.
- **Frontend** : Interface utilisateur développée avec Next.js / React, pour la visualisation des indicateurs et tableaux de bord.
- **Modèle de machine learning** : Modèle XGBoost entraîné sur des caractéristiques extraites des données de suivi, pour la prédiction de risques.
- **Base de données** : PostgreSQL pour la persistance des données structurées.
- **Conteneurisation** : Docker pour l'environnement de développement et de déploiement.
- **Intégration continue** : Pipeline CI/CD via GitHub Actions.

## Structure du projet

```
backend/    Code source de l'API FastAPI et du module de prédiction
frontend/   Application Next.js
config/     Fichiers de configuration (environnement, déploiement)
data/       Jeux de données et scripts de préparation
docs/       Documentation technique du projet
storage/    Gestion du stockage des fichiers
```

## Statut

Projet en développement actif. Les prochaines étapes incluent l'entraînement complet du modèle de prédiction sur un jeu de données étendu, la mise en place de tests automatisés et le déploiement d'une version de démonstration.

## Auteur

Steven Divin ITERITEKA — étudiant en Master 1 Acquisition et Traitement des Données Multidimensionnelles, Université Grenoble Alpes.
