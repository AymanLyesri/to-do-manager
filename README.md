# Cahier de charges

## Titre : Gestion des taches

**Gestion des taches**

| Version  |                                                 Auteur(s)                                                 | Approbation |
| :------- | :-------------------------------------------------------------------------------------------------------: | ----------: |
| initiale | **[AYMAN_LYESRI](https://github.com/AymanLyesri)** && **[YASSINE_TADLAOUI](https://github.com/Gri-ffin)** |           - |

## Perimetre du projet

1. But

   Etude, la conception et la réalisation d’un système de gestion
   de taches, couvrant les modules suivants :

   - creation des taches
   - gestion des clients
   - gestion des taches sauvegarde

2. Mission

   - Etude technique
   - Etude fonctionnelle
   - Conception
   - Realisation
   - Deploiement
   - Documentation

3. Livrables

| livrables         |    phase    | date de livraison | etat |
| :---------------- | :---------: | ----------------: | :--: |
| cahier de charges | realisation |                 - |      |
| code source       | realisation |                 - |      |

4. Contraints

   - delais : fin de semestre
   - technologie : [_Angular Js_](https://angular.io/), [_Nodejs_](https://nodejs.org/en/)

## Etude de l'existant

1. Concept metier

2. Logiciels similaires
   - [ Trello ](https://trello.com/)
   - [ Notion ](https://www.notion.so/)
   - [ Simple Note ](https://simplenote.com/)

## Etude fonctionnelle

1. Objectifs fonctionnels

2. Besoins fonctionnels

   2.1. Bloc fonctionnel : Gestion des taches

   - Fonctionnalités:
     Ce bloc permet la generation et la manipulation des Taches pour le compte des utilisateurs, il couvre les fonctionnalités suivantes :

   - Pour les taches:

     - Le système permet la ajout d'une tache a partir d'un texte.
     - Le système permet la modification des taches.
     - Le système permet de supprimer des taches.
     - Le système permet de valider une tache.

   - Pour les utilisateurs:

     - Le système permet de creer des comptes a des nouveaux utilisateurs.
     - Le système permet de gérer les taches pour chaque utilisateur.

   Règles de gestion

   | Réf   | Description                                                                                                                  |
   | :---- | :--------------------------------------------------------------------------------------------------------------------------- |
   | RG 01 | La tache génerée est compose de: <ul><li>ID de tache</li><li>Titre</li><li>ID de utilisateur</li><li>contenu</li></ul> |
   | RG 02 | ID est génerée automatiquement                                                                                               |
   | RG 03 | L'utilisateur peut avoir plusieurs taches                                                                                  |
   | RG 04 | L'utilisateur peut modifier plusieurs taches                                                                                |
   | RG 05 | L'utilisateur peut etre admin ou developeur                                                                     |
   | RG 06 | L'utilisateur peut supprimer plusieurs taches                                                                                  |
