---
title: MonVieuxGrimoire
publishDate: 2023-13-12 00:00:20
img: /assets/book.png
img_alt: image site web MonVieuxGrimoire
description: |
  Développement du backend pour le site "Mon vieux grimoire" en collaboration avec un développeur front-end, avec utilisation de NodeJS et Express, intégration de MongoDB, structuration modulaire du code, renforcement de la sécurité, et optimisation des images pour respecter les bonnes pratiques du Green Code.
tags:
  - MERN
  - API RESTful
  - GreenCode
---

Lien code GitHub : https://github.com/JulieFablet/Projet_MonVieuxGrimoire.git

#### Contexte

En tant que développeur back-end freelance, je collabore avec Kevin, un développeur front-end, sur la création du site "Mon vieux grimoire" pour le client "Le Vieux Grimoire", une chaîne de librairies. Mon rôle consiste à développer le backend du site en mettant en place l'API, utilisant NodeJS et le framework Express. Kevin a terminé le front-end et m'a envoyé les spécifications techniques de l'API ainsi que le code sur Github. Il souligne l'importance de prendre en compte la taille des images pour respecter les bonnes pratiques du Green Code, et donc d'optimiser les images dans le backend.

#### Problématique

Cette expérience marque ma première réalisation en tant que développeur back-end, suscitant des interrogations telles que : Comment développer le backend d'un site avec NodeJS et Express? Comment stocker les données de l'application? Comment optimiser les images dans le backend?

#### Réalisation

Pour surmonter ces défis, j'ai suivi des cours sur Openclassrooms pour maîtriser NodeJS et Express, concevoir une architecture modulaire, et intégrer une base de données. J'ai amorcé le projet avec NodeJS, installé Express, et créé une base de données sur MongoDB, que j'ai connectée au projet. J'ai structuré le code en séparant la logique de routing et la logique métier des routes, pour obtenir une structure modulaire. J'ai créé un dossier "Controller" pour la logique métier, un dossier "Route" pour la logique de routing, et un dossier "Model" pour les schémas mongoose des données de la base de données. Pour une modularité accrue, j'ai ajouté un dossier "Middleware" regroupant les middlewares traitant les requêtes avant leur destination finale. J'ai renforcé la sécurité de l'application et de la base de données en utilisant différents packages, middlewares et plugins tels que Helmet, Bcrypt, Express , Mongoose Unique Validator, etc. Enfin, j'ai optimisé les images en créant un middleware sharp, basé sur la bibliothèque sharp, pour redimensionner et compresser les images.