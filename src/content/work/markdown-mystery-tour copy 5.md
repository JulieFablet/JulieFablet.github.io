---
title: Kasa
publishDate: 2023-13-12 00:00:15
img: /assets/kasa.png
img_alt: Image site web kasa
description: |
 Création d'une application web de location immobilière pour Kasa, leader de la location entre particuliers en France.
tags:
  - React
  - React Router
  - SASS
---

Lien du site: https://juliefablet.github.io/Kasa/ 

Lien code GitHub : https://github.com/JulieFablet/Kasa.git

#### Contexte

Kasa, expert de la location entre particuliers en France depuis 10 ans, a récemment effectué une refonte complète de son site sous la direction de Laura, la CTO. Vous êtes recruté en tant que développeur front-end freelance par Kasa avec pour mission la création d'une application web de location immobilière en utilisant React

#### Problématique

N'étant pas familier avec ReactJS, ma principale problématique était de comprendre comment réaliser une application web avec cette technologie.

#### Réalisation

Pour surmonter cette problématique, j'ai suivi l'ensemble des cours proposés par Openclassrooms pour apprendre ReactJS. J'ai amorcé le projet avec CRA, en structurant soigneusement le code. J'ai adopté une logique de page unique (Single Page) avec la gestion du routage assurée par React Router dans le fichier App.js, où le composant App est créé. Le rendu de ce composant est effectué dans le fichier index.js à la racine du projet React, lequel crée le point d'ancrage dans le DOM (ID ROOT) pour l'application. Cette architecture comprend un dossier "components" regroupant des composants réutilisables (chaque composant ayant ses propres fichiers CSS et JSX) et un dossier "pages" comprenant les composants des différentes pages de l'application. Ces composants réutilisables sont intégrés dans les composants des pages, et ces derniers sont ensuite rendus dans le composant App.