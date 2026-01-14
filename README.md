# Multiplayer Interactive Fiction | Twine Extension (MIF-T)

> ℹ️ **Ce projet est actuellement en cours de développement. Il n'est pas encore finalisé et peut présenter des bugs ou des comportements inattendus.**

Ce projet contient un fichier `mift.twee` qui est une histoire interactive multijoueur conçue pour Twine avec l'extension MIF-T (Multiplayer Interactive Fiction for Twine).

## Prérequis
- Navigateur web moderne (Chrome, Firefox, Edge, etc.)
- [Twine Web](https://twinery.org/2/) (utilisation recommandée via le site officiel)

## Importer le fichier dans Twine Web
1. Rendez-vous sur [https://twinery.org/2/](https://twinery.org/2/).
2. Cliquez sur l'onglet **"Library"** puis choisissez **"Import"**.
3. Sélectionnez le fichier `mift.twee` présent dans ce dossier.
4. L'histoire apparaîtra dans votre bibliothèque Twine.

## Lancer et tester l'histoire
1. Cliquez sur l'histoire importée pour l'ouvrir.
2. Cliquez sur l'onglet **"Build"** puis choisissez **"Test"** pour lancer la démo.

## Fonctionnalités principales
- **Multijoueur sans serveur** : fonctionne via PeerJS/WebRTC, aucune installation serveur requise.
- **Modes de décision** : majority, leader, individual, exclusive (voir l'histoire pour la démo de chaque mode).
- **Synchronisation automatique** : l'hôte gère la logique et synchronise tous les clients.

## Ressources utiles
- Documentation Twine : https://twinery.org/wiki/twine2:guide
- Documentation SugarCube : https://www.motoslave.net/sugarcube/2/docs/
- PeerJS : https://peerjs.com/