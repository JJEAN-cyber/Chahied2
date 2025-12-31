# Chahied2
Développement d'une marketplace de vente de vêtements en ligne.

Marketplace de Vente de Vêtements — Java MVC (Servlets + JSP)
Application web monolithique Java développée avec Servlets, JSP et une architecture MVC, permettant aux utilisateurs d’acheter, vendre et rechercher des vêtements.
Le projet inclut une messagerie interne, un panneau d’administration, un système de catégories, ainsi qu’une catégorie spéciale dédiée à l’échange de vêtements pendant les fêtes.

✨ Fonctionnalités principales
🛍️ Marketplace
- Création de compte utilisateur
- Mise en vente d’articles (titre, description, prix, photos)
- Consultation des annonces
- Filtrage et recherche avancée
- Gestion du profil vendeur
- Espace “Catégories” pour organiser les vêtements
- Catégorie spéciale “Échange de vêtements (Fêtes)” permettant aux utilisateurs d’échanger des articles pendant les périodes festives

🔎 Barre de recherche
- Recherche de vêtements par :
- nom
- catégorie
- prix
- mots‑clés
- Recherche de profils utilisateurs
- Recherche filtrée par catégorie, y compris la catégorie spéciale d’échange

💬 Messagerie interne
- Échanges entre utilisateurs
- Messagerie asynchrone (pas de WebSocket)
- Historique des conversations

🛠️ Panneau administrateur
- Tableau de bord administrateur
- Gestion des utilisateurs
- Gestion des annonces
- Gestion des catégories (y compris la catégorie spéciale)
- Modération (validation / suppression)
- Vue d’ensemble de l’activité du site

🔐 Sécurité & gestion
- Authentification
- Sessions utilisateurs
- Rôles (Utilisateur / Administrateur)
- Validation des données

🧱 Architecture & Technologies
|  |  | 
|  |  | 
|  |  | 
|  |  | 
|  | .sql | 
|  |  | 
|  |  | 
|  |  | 



📂 Structure du projet
Chahied2/
│
├── src/
│   ├── controllers/      -> Servlets (logique de contrôle)
│   ├── dao/              -> Accès base de données
│   ├── models/           -> Objets métiers (User, Product, Message, Category…)
│   └── services/         -> Logique applicative
│
├── webapp/
│   ├── WEB-INF/
│   │   └── views/        -> JSP (vues)
│   └── assets/           -> CSS, JS, images
│
├── database.sql          -> Script SQL (tables + données)
└── README.md



🚀 Installation & exécution
1. Importer le projet dans un IDE Java
Compatible avec :
- IntelliJ IDEA
- Eclipse
- NetBeans
2. Configurer la base de données
Importer le fichier :
database.sql


Puis configurer la connexion dans ton fichier Java (ex : DBConnection.java) :
- URL JDBC
- utilisateur
- mot de passe
3. Déployer sur un serveur Java
Exemple : Apache Tomcat
4. Lancer l’application
Accéder via :
http://localhost:8080/Chahied2



🖥️ Utilisation
- Créer un compte utilisateur
- Parcourir les vêtements disponibles
- Mettre en vente ses propres articles
- Utiliser la barre de recherche
- Explorer les catégories
- Accéder à la catégorie spéciale “Échange de vêtements (Fêtes)”
- Envoyer des messages via la messagerie interne
- Accéder au tableau de bord administrateur (si rôle Admin)

🗺️ Roadmap
- Messagerie en temps réel (WebSocket)
- Notifications
- Paiement sécurisé
- Système d’avis et de notation
- Version mobile responsive
- Recommandations IA
- Événements saisonniers supplémentaires (Halloween, été, rentrée…)

👤 Auteur
Jonathan
Développeur Java (CDA) & apprenant Expert IA



