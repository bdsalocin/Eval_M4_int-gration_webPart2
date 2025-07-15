# Projet : Intégration de maquettes "Ghost Blog"

## Table des matières

1.  [Introduction](#1-introduction)
2.  [Objectif du projet](#2-objectif-du-projet)
3.  [Fonctionnalités](#3-fonctionnalités)
4.  [Technologies Utilisées](#4-technologies-utilisées)
5.  [Structure des fichiers](#5-structure-des-fichiers)
6.  [Installation et exécution](#6-installation-et-exécution)
7.  [Responsivité](#7-responsivité)
8.  [Améliorations futures possibles](#8-améliorations-futures-possibles)
9.  [Auteur](#9-auteur)
10. [Licence](#10-licence)

---

## 1. Introduction

Ce projet est une intégration HTML/CSS d'une maquette de blog fictif appelée "Ghost Blog". [cite_start]Il s'agit d'une évaluation pour démontrer les compétences en intégration web, en respectant un design donné et en assurant la responsivité pour différentes tailles d'écran. [cite: 7]

## 2. Objectif du projet

L'objectif principal était de traduire des maquettes visuelles (page d'accueil et page contact) en code HTML et CSS valide et sémantique. Un accent particulier a été mis sur :
* [cite_start]L'utilisation de balises sémantiques pour une structure HTML claire et accessible. [cite: 8]
* [cite_start]L'adaptation du design aux supports mobiles et tablettes (responsivité). [cite: 7]
* [cite_start]L'intégration du framework CSS Bootstrap 4. [cite: 15]
* [cite_start]L'utilisation de la librairie d'icônes Font Awesome pour les éléments sociaux. [cite: 15]

## 3. Fonctionnalités

* **Page d'accueil :**
    * En-tête (Header) avec navigation et liens sociaux.
    * Section héro avec titre et sous-titre du blog.
    * Affichage d'articles sous forme de cartes, organisés en différentes sections.
    * Structure de grille responsive pour un affichage optimal sur divers appareils.
* **Page contact :**
    * Formulaire de contact complet (Nom, Prénom, Catégorie, Téléphone, Email, Choix de l'heure, Inscription newsletter).
    * Design conforme à la maquette fournie.
    * Utilisation des éléments de formulaire Bootstrap pour la stylisation.
    * Année de copyright mise à jour dynamiquement via JavaScript dans le pied de page.
* **Navigation :**
    * Barre de navigation simple et claire dans l'en-tête.
    * Liens vers les réseaux sociaux (Facebook, Twitter).
* **Design :**
    * Utilisation de la charte graphique de la maquette (couleurs, espacements, typographie).
    * Images fluides s'adaptant à la taille du conteneur.

## 4. Technologies Utilisées

* **HTML5** (pour la structure sémantique du contenu)
* **CSS3** (pour le stylisme personnalisé)
* [cite_start]**Bootstrap 5** (framework CSS pour la grille, les composants et la responsivité) [cite: 15]
* [cite_start]**Font Awesome 5.15.4** (pour les icônes) [cite: 15]

## 5. Structure des fichiers

├── images/
│   ├── 0.png
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   └── 6.png
├── contact.html
├── index.html
├── M4 - TD-1 - Intégration HTML CSS.pdf
├── README.md
└── style.css

## 6. Installation et exécution

Pour visualiser le projet localement :

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/bdsalocin/Eval_M4_int-gration_webPart2.git](https://github.com/bdsalocin/Eval_M4_int-gration_webPart2.git)
    cd Eval_M4_int-gration_webPart2
    ```
2.  **Ouvrir les fichiers :**
    * Ouvrez le fichier `index.html` dans votre navigateur web préféré.

Aucune dépendance serveur ou compilation n'est nécessaire car il s'agit d'un projet d'intégration front-end pur.

## 7. Responsivité

Le projet est conçu pour être entièrement responsive. Les points clés de la responsivité incluent :
* **Meta Tag Viewport :** Essentiel pour l'affichage correct sur mobile.
* **Grille Bootstrap :** Utilisation intensive des classes `.col-sm-`, `.col-md-`, `.col-lg-` pour adapter la disposition des éléments (en particulier les cartes d'articles et les champs de formulaire) en fonction de la taille de l'écran.
* **`img-fluid` :** Toutes les images s'adaptent à la largeur de leur conteneur.
* **Classes utilitaires Bootstrap :** Utilisation de classes comme `d-flex`, `justify-content-center`, `align-items-stretch`, `text-center`, `text-md-left` pour contrôler le comportement et l'alignement des éléments à différents breakpoints.