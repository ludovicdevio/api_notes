# Projet API avec Express et MongoDB

Ce projet est une API de prise de note développée en JavaScript utilisant Express comme framework web et MongoDB comme base de données.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants sur votre machine :

- Node.js
- npm (gestionnaire de packages pour Node.js)
- MongoDB
- Express

## Installation

1. Clonez ce dépôt sur votre machine en utilisant la commande suivante : https://github.com/ludovicdevio/api_notes/

2. Accédez au répertoire du projet depuis l'invite de commandes

3. Installez les dépendances en exécutant la commande : `npm install`

## Configuration

4. Assurez-vous d'avoir une instance de MongoDB en cours d'exécution sur votre machine, ou configurez l'URL de connexion dans le fichier `config/db.js`. Configurez `DB_USER_PASS` dans le fichier `.env`.

## Démarrage du serveur

Pour lancer le serveur, exécutez la commande suivante depuis la racine du projet :`npm start`

## Utilisation de l'API

L'API expose plusieurs endpoints pour interagir avec les données stockées dans la base de données. Voici quelques exemples d'utilisation :

router.get("/", getPosts);
router.post("/", setPosts);
router.put("/:id", editPost);
router.delete("/:id", deletePost);
router.patch("/like-post/:id", likePost);
router.patch("/dislike-post/:id", dislikePost);
"# api_notes" 
