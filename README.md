# Ecommerce 

## Description du projet :

Ce projet vise à créer une application de commerce en ligne en backend, en utilisant Express.js pour gérer les sessions utilisateur 
et l'API Stripe pour simplifier les paiements en ligne. L'objectif est de permettre à un utilisateur de parcourir des produits, 
d'ajouter des éléments à son panier, de réaliser un paiement sécurisé et de gérer les erreurs de manière adéquate.

## Technologies utilisées :

- **Node.js et Express.js** pour le serveur backend

- **Stripe API** pour gérer les paiements en ligne
  
- **MongoDB** pour stocker les produits et les sessions
  
- **dotenv** pour gérer les variables d'environnement
  
- **Express Router** pour gérer les routes de l'application

## Caractéristiques :

- **Créer des variables d'environnement avec dotenv** : Gestion des informations sensibles comme les clés API Stripe et les configurations d'environnement via le fichier .env.
  
- **Créer les différentes pages avec Express Router** : Organisation du projet avec des routes dédiées pour chaque fonctionnalité (produits, panier, paiement).
  
- **Insérer des produits en base de données** : Création d'un modèle de produits dans la base de données MongoDB, et insertion de produits pour peupler le catalogue.
  
- **Afficher dynamiquement les différents produits** : Affichage des produits récupérés dynamiquement depuis la base de données sur la page du catalogue.
  
- **Personnaliser l'expérience utilisateur grâce aux sessions** : Utilisation des sessions Express pour suivre l'utilisateur pendant sa navigation, 
lui permettant de personnaliser son expérience (panier, informations de paiement).

- **Créer une session Express** : Création d'une session utilisateur pour garder une trace de son panier tout au long de la session.
  
- **Ajouter un produit au panier** : Permettre à l'utilisateur d'ajouter des produits à son panier et de mettre à jour la session en conséquence.
  
- **Affichage du contenu du panier** : Affichage des éléments du panier de l'utilisateur avec les informations de prix et quantité.
  
- **Supprimer un élément du panier** : Implémentation de la fonctionnalité permettant de supprimer un ou plusieurs produits du panier.
  
- **Simplifier vos paiements avec Stripe** : Intégration de l'API Stripe pour faciliter les paiements sécurisés.
  
- **Créer une session de paiement** : Création d'une session de paiement Stripe, permettant à l'utilisateur de passer à l'étape de paiement.
  
- **Paiement réussi ou échoué** : Traitement des résultats de paiement via Stripe, en gérant les cas de succès et d'échec.
  
- **Middleware de gestion d'erreurs** : Mise en place d'un middleware pour gérer les erreurs au niveau du serveur.
  
- **Erreur 404** : Gestion des erreurs 404 pour afficher une page d'erreur appropriée si l'utilisateur tente d'accéder à une page inexistante.

