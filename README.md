# 🛒 Marketplace E-Commerce Multi-Vendeurs  
Plateforme complète de marketplace multi-vendeurs développée avec **Oracle Database**, **PL/SQL** et **Oracle APEX**.

---

## 📋 Table des Matières
- 🚀 Aperçu du Projet  
- ✨ Fonctionnalités  
- 📊 Modélisation  
- 🗄️ Structure de la Base de Données  
- 🔧 Installation  
- 📖 Utilisation  
- 📚 Documentation  
- 👥 Auteurs  
- 📄 Licence  

---

## 🚀 Aperçu du Projet

Ce projet consiste à concevoir et développer une **marketplace e-commerce multi-vendeurs** en utilisant :

- Oracle Database  
- PL/SQL  
- Oracle APEX  

Objectifs principaux :

- 🎯 Maîtriser la modélisation **MERISE**  
- 🗄️ Implémenter une base Oracle relationnelle  
- 🧠 Développer la logique métier complète en PL/SQL  
- 🖥️ Créer une interface web avec Oracle APEX  
- 🧩 Appliquer les bonnes pratiques de modélisation et de développement  

---

## ✨ Fonctionnalités

### 👤 Pour les Clients
- ✅ Inscription & authentification  
- ✅ Consultation du catalogue produits  
- ✅ Recherche avancée  
- ✅ Gestion du profil  
- ✅ Ajout au panier  
- ✅ Passage de commande  
- ✅ Paiement en ligne  
- ✅ Suivi des commandes & expédition  
- ✅ Dépôt d'avis  
- ✅ Demande de remboursement  

### 🏪 Pour les Vendeurs
- ✅ Gestion de la boutique  
- ✅ CRUD complet sur les produits  
- ✅ Gestion des stocks  
- ✅ Consultation du chiffre d'affaires  
- ✅ Application des coupons  
- ✅ Gestion des statuts de commande  
- ✅ Supervision des ventes  
- ✅ Gestion des transactions  

### 🛡️ Pour les Administrateurs
- ✅ Gestion des utilisateurs (CRUD)  
- ✅ Gestion des catégories  
- ✅ Journalisation des actions sensibles  
- ✅ Consultation des logs système  

---

## 📊 Modélisation

### 📘 Modèle Conceptuel de Données (MCD)

Entités principales :

- **Vendeur** : gère les produits et la boutique  
- **Client** : passe des commandes et donne des avis  
- **Produit** : appartient à une catégorie et proposé par un vendeur  
- **Commande** : ensemble de lignes produits  
- **Ligne_Commande** : produit + quantité  
- **Paiement** : transaction associée à une commande  
- **Expédition** : livraison d’une commande  
- **Avis** : évaluation d’un produit  
- **Coupon** : réduction appliquée aux commandes  
- **Log_Actions** : journal d’audit  

### 🧠 Règles de Gestion
- Décrémentation automatique du stock  
- Workflow des statuts : **Pending → Paid → Shipped**  
- Vérification du stock avant commande  
- Application automatique des coupons  
- Journalisation complète des actions critiques  

---

## 🗄️ Structure de la Base de Données

### 📦 Tables Principales
- `CATEGORIE`  
- `VENDEUR`  
- `CLIENT`  
- `COUPON`  
- `PRODUIT`  
- `COMMANDE`  
- `LIGNE_COMMANDE`  
- `PAIEMENT`  
- `EXPEDITION`  
- `AVIS`  
- `LOG_ACTIONS`  

### 🔗 Relations Clés
- 1 vendeur → N produits  
- 1 catégorie → N produits  
- 1 client → N commandes  
- 1 commande → N lignes  
- 1 ligne → 1 produit  
- 1 commande → 1 paiement  
- 1 commande → 1 expédition  
- 1 produit → N avis  

---

## 🔧 Installation

### 📌 Prérequis
- Oracle Database **21c XE** ou supérieur  
- Oracle SQL Developer  
- Oracle APEX **22.2+**  