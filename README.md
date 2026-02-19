# VR Archery Challenge

# Introduction

[![Démo vidéo](https://drive.usercontent.google.com/download?id=1XIKCXUbKyO2CTuHfKYZHCSTZr9vLjkij)](https://www.youtube.com/watch?v=fguW0s58Nlc)

**VR Archery Challenge** est une simulation de tir à l'arc en réalité virtuelle conçue pour offrir une expérience immersive et physique. Le projet se concentre sur la reproduction fidèle des gestes réels : de la saisie de l'arc à l'encoche de la flèche, jusqu'à la tension de la corde pour atteindre des cibles dynamiques.

## Index

- [About](#about)
- [Usage](#usage)
  - [Exécution du Projet](#exécution-du-projet)
  - [Commandes](#commandes)
- [Development](#development)
  - [Pré-requis](#pré-requis)
  - [Environnement de Développement](#environnement-de-développement)
- [Crédits](#crédits)

## About

Le but principal de ce projet était de simuler les mouvements naturels avec des manettes VR. En utilisant **Unity XR Interaction Toolkit**, nous avons développé un système où l'interaction ne se limite pas à un simple bouton, mais à une coordination motrice précise.

**Points clés du projet :**
- **Système d'armes évolutif :** Choix entre deux types d'arcs et deux types de flèches, chacun possédant ses propres caractéristiques de puissance et de vitesse.
- **Progression de difficulté :** 3 niveaux (Facile, Moyen, Difficile) avec des cibles de tailles différentes, des vitesses de déplacement variables et une contrainte de temps croissante.
- **Mode Entraînement :** Une scène dédiée pour s'exercer sur des cibles fixes sans pression de score.
- **Système de Score Complet :** Sauvegarde locale des performances (Nom, Score, Difficulté) avec un affichage des meilleurs scores via un classement.



## Usage

Le projet est conçu pour être exécuté directement depuis l'éditeur Unity. Aucun build (.exe ou .apk) n'est fourni.

### Exécution du Projet

1. **Connexion VR** : Connectez votre casque (Oculus/Meta Quest via Link, ou tout casque compatible SteamVR).
2. **Ouverture** : Lancez Unity Hub et ouvrez le projet avec la version **2022.3.62f3**.
3. **Point d'entrée** : Naviguez dans le dossier `Assets/Scenes/` et ouvrez la scène **MainMenuScene**.
4. **Play Mode** : Cliquez sur le bouton **Play** dans l'éditeur Unity pour lancer l'expérience.

### Commandes

- **Saisir l'Arc** : Gâchette latérale (Grip) de la main principale.
- **Prendre une Flèche** : Gâchette latérale (Grip) de la main secondaire (derrière l'épaule).
- **Encocher et Tirer** : Maintenir la gâchette d'index (Trigger) près de la corde, tirer en arrière, puis relâcher.
- **Interactions Menu** : Pointer avec le rayon laser et valider avec la gâchette d'index (Trigger).

## Development

Cette section explique comment configurer l'environnement pour modifier le projet.

### Pré-requis

- Unity Hub.
- Unity Editor version **2022.3.62f3**.
- XR Plugin Management & XR Interaction Toolkit installés via le Package Manager.

### Environnement de Développement

1. **Clonage du projet** :
   ```bash
   $ git clone https://github.com/acrazypotterhead/Projet-arc-VR/
   ```

2. **Configuration Unity** :  
   Ajoutez le projet dans Unity Hub en respectant scrupuleusement la version 2022.3.62f3 pour éviter les ruptures de liens du XR Toolkit.

### Crédits
Ce projet a été réalisé en binôme en 4ème année d'école d'ingénieur :
- [Alexandre Baudin](https://github.com/Antiflex)
- [Jessica Rasoamanana](https://github.com/acrazypotterhead)
   
