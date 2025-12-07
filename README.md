🛒 Marketplace E-Commerce Multi-Vendeurs

Développé avec Oracle Database, PL/SQL et Oracle APEX

📚 Table des Matières

🚀 Aperçu du Projet

✨ Fonctionnalités

📊 Modélisation

🗄️ Structure de la Base de Données

🔧 Installation

📖 Utilisation

📘 Documentation

👥 Auteurs

📄 Licence

🚀 Aperçu du Projet

Cette plateforme e-commerce multi-vendeurs a été développée dans un contexte académique pour mettre en pratique :

Modélisation MERISE

Développement PL/SQL

Réalisation d’interfaces avec Oracle APEX

Bonnes pratiques de développement d’applications complètes

🎯 Objectif principal : Concevoir une marketplace fonctionnelle permettant aux vendeurs de gérer leurs produits, aux clients d’acheter, et aux administrateurs de superviser l’ensemble du système.

✨ Fonctionnalités
👤 Pour les Clients

✅ Inscription & Authentification

✅ Consultation du Catalogue

✅ Recherche de Produits

✅ Gestion du Profil

✅ Panier d’Achat

✅ Passation de Commande

✅ Paiement en Ligne

✅ Suivi des Commandes & Expéditions

✅ Dépôt d’Avis

✅ Demande de Remboursement

🛍️ Pour les Vendeurs

✅ Gestion de la Boutique

✅ CRUD Produits

✅ Gestion des Stocks

✅ Suivi Chiffre d’Affaires

✅ Application de Coupons

✅ Gestion des Commandes

✅ Supervision des Ventes

✅ Gestion des Transactions

🛠️ Pour les Administrateurs

✅ Gestion des Utilisateurs (CRUD)

✅ Gestion des Catégories

✅ Journalisation des Actions Sensibles

✅ Consultation des Logs Système

📊 Modélisation
🧩 Modèle Conceptuel (MERISE)

Entités principales :

Vendeur

Client

Produit

Commande

Ligne_Commande

Paiement

Expédition

Avis

Coupon

Log_Actions

🔐 Règles de Gestion

Gestion automatique des stocks

Workflow commandes : Pending → Paid → Shipped

Validation des statuts

Contrôle des stocks avant commande

Application automatique des coupons

Journalisation des opérations

🗄️ Structure de la Base de Données
📌 Tables Principales

CATEGORIE

VENDEUR

CLIENT

COUPON

PRODUIT

COMMANDE

LIGNE_COMMANDE

PAIEMENT

EXPEDITION

AVIS

LOG_ACTIONS

🔗 Relations

1 vendeur → N produits

1 catégorie → N produits

1 client → N commandes

1 commande → N lignes

1 ligne → 1 produit

1 commande → 1 paiement

1 commande → 1 expédition

1 client → N avis

🔧 Installation
📋 Prérequis

Oracle Database 21c XE+

Oracle SQL Developer

Oracle APEX 22.2+

🛠️ Étapes d’installation
1️⃣ Cloner le dépôt
git clone https://github.com/votre-username/marketplace-ecommerce.git
cd marketplace-ecommerce

Université Cadi Ayyad – FSSM
Département Informatique – 2024/2025

📄 Licence

Projet réalisé dans un cadre académique.