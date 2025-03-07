# Ecommerce 🛒💳

## Description du projet :
Ce projet a pour but de créer une application de commerce en ligne en backend, utilisant **Express.js** pour gérer les sessions utilisateur et **Stripe** pour les paiements en ligne. L'objectif est de permettre à un utilisateur de parcourir des produits, d'ajouter des éléments à son panier, de réaliser un paiement sécurisé et de gérer les erreurs de manière adéquate. 🛍️

## Technologies utilisées : 🛠️
- **Node.js & Express.js** : pour le serveur backend 🚀.
- **Stripe API** : pour la gestion des paiements en ligne 💳.
- **MongoDB** : pour stocker les produits et les sessions 💾.
- **dotenv** : pour la gestion des variables d'environnement 🔐.
- **Express Router** : pour organiser les routes de l'application 🛤️.

## Fonctionnalités : ✨
- **Variables d'environnement avec dotenv** : Gestion des informations sensibles comme les clés API Stripe via un fichier `.env` 🔑.
- **Routes avec Express Router** : Organisation du projet avec des routes dédiées pour chaque fonctionnalité (produits, panier, paiement) 🛒.
- **Insertion de produits en base de données** : Création d'un modèle de produits et insertion dans la base MongoDB 📦.
- **Affichage dynamique des produits** : Affichage des produits récupérés depuis la base de données sur la page du catalogue 📃.
- **Sessions utilisateur personnalisées** : Utilisation des sessions Express pour suivre l'utilisateur et personnaliser son expérience (panier, informations de paiement) 🧑‍💻.
- **Création et gestion de session** : Suivi du panier de l'utilisateur tout au long de la session 🔄.
- **Ajout au panier** : Permet à l'utilisateur d'ajouter des produits au panier et de mettre à jour la session 🛍️.
- **Affichage du panier** : Présentation des produits du panier avec leurs prix et quantités 🏷️.
- **Suppression d'éléments du panier** : Fonctionnalité permettant de retirer des produits du panier ❌.
- **Paiements sécurisés avec Stripe** : Intégration de Stripe pour gérer les paiements 💳.
- **Session de paiement Stripe** : Création d'une session Stripe pour initier le paiement sécurisé 🔒.
- **Résultats de paiement** : Traitement des paiements réussis ou échoués via Stripe ✅❌.
- **Middleware de gestion des erreurs** : Mise en place d'un middleware pour gérer les erreurs au niveau du serveur ⚠️.
- **Erreur 404** : Gestion des erreurs 404 avec une page dédiée en cas de lien cassé 🚫.

## Installation et lancement : 🚀
1. Clonez ce repository sur votre machine.
2. Installez les dépendances avec `npm install`.
3. Créez un fichier `.env` avec vos clés API Stripe et MongoDB.
4. Lancez le serveur avec `npm start` 🔥.

## Fonctionnalités principales : 🎯
- Parcourir des produits et les ajouter au panier 🛒.
- Passer à l'étape de paiement avec Stripe 💳.
- Gérer les sessions utilisateurs et personnaliser l'expérience utilisateur 🧑‍💻.
