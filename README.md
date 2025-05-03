# AgroConnect

## Description du Projet

AgroConnect est une plateforme de mise en relation entre agriculteurs et acheteurs au Cameroun. Elle permet aux agriculteurs de publier leurs produits et aux acheteurs de les découvrir et de passer commande, favorisant ainsi le commerce local et l'agriculture durable.

## Fonctionnalités Implémentées

### Authentification et Gestion des Utilisateurs
- Système d'authentification complet avec Supabase
- Gestion des rôles utilisateur (agriculteur, acheteur, admin)
- Profils utilisateurs personnalisables

### Interface Utilisateur Unifiée
- Tableau de bord moderne et intuitif qui s'adapte au rôle de l'utilisateur
- Navigation simplifiée avec accès direct aux fonctionnalités principales
- Design responsive pour une expérience optimale sur tous les appareils
- Cartes de fonctionnalités minimalistes avec icônes centrées et descriptions concises

### Autres Fonctionnalités
- Affichage des statistiques pertinentes selon le rôle utilisateur
- Suivi des activités récentes
- Gestion des produits agricoles pour les agriculteurs
- Exploration du marché pour les acheteurs
- Interface d'administration pour les gestionnaires de la plateforme

## Technologies Utilisées

- **Frontend**: React, TypeScript, Material UI
- **Backend**: Supabase (PostgreSQL, Authentication, Storage)
- **Déploiement**: À déterminer (probablement Vercel ou Netlify)

## À Faire

### Développement Court Terme
- Implémentation complète de la gestion des produits
- Système de messagerie entre agriculteurs et acheteurs
- Gestion des commandes et processus de paiement
- Résolution des problèmes de Row Level Security (RLS) dans Supabase

### Développement Moyen Terme
- Système de notation et d'avis pour les produits et les vendeurs
- Analytiques avancées pour les agriculteurs
- Système de recherche avancé avec filtres
- Notifications en temps réel

### Développement Long Terme
- Application mobile native (React Native)
- Intégration avec des services de paiement locaux au Cameroun
- Cartographie des agriculteurs et points de vente
- Système de prévision de récolte basé sur des données historiques

## Installation et Démarrage

```bash
# Cloner le dépôt
git clone https://github.com/projets-de-Pony/agro.git
cd agro

# Installer les dépendances
npm install

# Démarrer l'application en mode développement
npm start
```

## Configuration

Créez un fichier `.env.local` à la racine du projet avec les variables suivantes :

```
REACT_APP_SUPABASE_URL=votre-url-supabase
REACT_APP_SUPABASE_ANON_KEY=votre-clé-anon-supabase
```

## Structure du Projet

```
src/
├── components/       # Composants réutilisables
│   ├── auth/         # Composants d'authentification
│   ├── layout/       # Layouts et templates
│   └── ui/           # Éléments d'interface utilisateur
├── pages/            # Pages de l'application
│   ├── users/        # Pages du tableau de bord utilisateur
│   ├── auth/         # Pages d'authentification
│   └── public/       # Pages accessibles sans authentification
├── utils/            # Utilitaires et helpers
├── services/         # Services API et logique métier
└── assets/           # Images, icônes, etc.
```

## Contribution

Les contributions sont bienvenues ! Veuillez créer une issue pour discuter des changements majeurs avant de soumettre une pull request.

---

Réalisé avec ❤️ par Pony Victor et Erica Diffo

Mai 2025
