<div align="center">

![Mon logo](https://danyella.works/logo.png)

</div>

<div align=center>

# Site web de Danyella Strikann <!-- omit in toc -->

</div>

<div align="center">

![Version](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2Fmovva-gpu%2FPortfolioV2%2Fraw%2Fdev%2Fpackage.json&query=%24.version&style=for-the-badge&label=version&labelColor=203&color=hotpink)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge&labelColor=203)
![Pug version](https://img.shields.io/badge/Pug-3.0-A86454?style=for-the-badge&logo=pug&logoColor=white&labelColor=203)
![Node.js version](https://img.shields.io/badge/Node-21.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=203)
![Express version](https://img.shields.io/badge/Express-4.18-259dff?style=for-the-badge&logo=express&logoColor=white&labelColor=203)

</div>

## Introduction

Ce site est mon plus gros projet web jusqu'ici, combinant un moteur de
template [Pug](https://pugjs.org), du back géré avec
[Express](https://expressjs.org) et donc [Node.js](https://nodejs.org),
ainsi que des animations avec [ScrollMagic](https://scrollmagic.io) et
[GSAP](https://gsap.com).

## Table des matières <!-- omit in toc -->

- [Introduction](#introduction)
- [Contenus](#contenus)
- [Fonctionnalités](#fonctionnalités)
  - [Accueil](#accueil)
  - [Portfolio](#portfolio)
  - [Projets](#projets)
  - [Toutes les pages](#toutes-les-pages)
  - [Back-end](#back-end)

## Contenus

- Une page d'accueil, contenant une petite présentation de moi
- Un portfolio, présentant certains de mes projets (Validity et ma SAE105)
- Une page recensant beaucoup plus de mes projets
- Mon C.V.
- Mon adresse mail et mon LinkedIn dans le menu

## Fonctionnalités

### Accueil

- Un effet de parallax avec GSAP
- Des animations déclenchées au scroll avec ScrollMagic
- Un effet de *brouillage* de texte sur une partie du deuxième paragraphe

### Portfolio

- Un effet de parallax sur la bannière hero avec le mouvement de la souris
- Du texte se déplaçant avec GSAP et ScrollMagic
- Un effet de *brouillage* de texte sur le titre de la section sur Validity
- Des boutons arc-en-ciels pour les liens des différentes sections
- Une transition lors d'un click sur l'un de ces boutons
- Encore plus d'animations ScrollMagic X GSAP

### Projets

- Un bouton incitant l'utilisateur à scroller vers le bas apparaissant
  avec ScrollMagic
- Une grille avec mes différents projets

### Toutes les pages

- Un menu animé avec GSAP
- Un bouton contenant des liens vers mes réseaux
- Du contenu responsive (mise à jour prévue pour le Portfolio)

### Back-end

- Distribution statique du dossier www/
- Routeurs pour faire le rendu des templates dans views/
- Utilisation du moteur de template Pug
- Gestion et affichage des erreurs
- Authentification requise pour accéder au dossier private/

-------------------------------------------------------------------------------

<div align="center">

Made with all my love 🤍

</div>
