# TvShowApp - Application Android de Séries TV

## Description du Projet
TvShowApp est une application Android moderne développée en Kotlin qui permet aux utilisateurs de découvrir et suivre leurs séries TV préférées. L'application utilise l'architecture MVVM (Model-View-ViewModel) et les dernières technologies Android recommandées.

## Technologies Utilisées
- **Langage**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **Interface Utilisateur**: Jetpack Compose
- **Injection de Dépendances**: Hilt
- **Base de Données**: Room
- **Appels Réseau**: Retrofit
- **Gestion des Images**: Coil
- **Navigation**: Jetpack Navigation Compose

## Fonctionnalités Principales
1. **Liste des Séries**
   - Affichage des séries populaires
   - Recherche de séries
   - Filtrage par catégories

2. **Détails des Séries**
   - Informations détaillées sur chaque série
   - Liste des épisodes
   - Notes et avis

3. **Gestion des Favoris**
   - Ajout/Suppression des séries aux favoris
   - Liste personnalisée des séries favorites

## Structure du Projet
```
app/
├── src/main/
│   ├── java/
│   │   └── com/example/tvshowapp/
│   │       ├── data/           # Couche données (API, Base de données)
│   │       ├── di/            # Injection de dépendances
│   │       ├── domain/        # Logique métier
│   │       ├── presentation/  # UI et ViewModels
│   │       └── utils/         # Utilitaires
│   └── res/                   # Ressources (images, strings, etc.)
```

## Configuration du Projet
1. Cloner le repository
2. Ouvrir le projet dans Android Studio
3. Synchroniser avec Gradle
4. Lancer l'application sur un émulateur ou un appareil Android

## Dépendances Principales
- Jetpack Compose pour l'UI
- Hilt pour l'injection de dépendances
- Retrofit pour les appels API
- Room pour la persistance des données
- Coil pour le chargement des images
- Navigation Compose pour la navigation

## Architecture
L'application suit les principes de Clean Architecture avec trois couches principales :
- **Présentation**: ViewModels et composants UI
- **Domaine**: Cas d'utilisation et modèles de données
- **Données**: Sources de données (API, Base de données locale)

## Contribution
Ce projet a été réalisé dans le cadre d'un projet académique. 
