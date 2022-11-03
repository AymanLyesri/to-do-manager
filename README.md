# Cahier de charges

## Titre : Project Ai Image Generation

**Generation et gestion des images en utlisant l'intelligence artificiel.** `stable diffusion`

| Version  |                 Auteur                   | Approbation  |
| :------- | :-------------------------------------:  | ----------:  |
| initiale | **AYMAN_LYESRI** && **YASSINE_TADLAOUI** |            - |

## Perimetre du projet

1. but

   - creation d'image
   - gestion des clients
   - gestion des images sauvegarde
   - gestion des version de stable diffusion

2. mission

   - Etude technique
   - Etude fonctionnelle
   - Conception
   - Realisation
   - Deploiement
   - Documentation

3. livrables

| livrable          |    phase    | date de livraison | etat |
| :---------------- | :---------: | ----------------: | :--: |
| cahier de charges | realisation |                 - |      |
| code source       | realisation |                 - |      |

4. contraints

   - delais : fin de semestre
   - technologie : `stable diffusion`, _Angular Js_, _Nodejs_

## Etude de l'existant

1. Concept metier

2. logiciels similaires
    - DALL-E

## Etude fonctionnelle

1. Objectifs fonctionnels

2. Besoins fonctionnels

    2.1. Bloc fonctionnel : Generation d'image

    - Fonctionnalités:
    Ce bloc permet la generation et la manipulation des images génerés pour le compte des utilisateurs, il couvre les fonctionnalités suivantes :

    - Pour les images:

        - Le système permet la generation d'une image a partir d'un texte.
        - Le système permet l'enregistrement des images.
        - Le système permet de supprimer des images.
        - Le système permet de liker une image.

    - Pour les utilisateurs:

        - Le système permet de creer des comptes a des nouveaux utilisateurs.
        - Le système permet de gérer les images pour chaque utilisateur.

    Règles de gestion

    | Réf   | Description                                                                                                          |
    | :---- | :-------                                                                                                             |
    | RG 01 | L'image génerée est compose de: <ul><li>ID</li><li>Titre</li><li>ID de utilisateur</li><li>Nombre de likes</li></ul> |
    | RG 02 | ID est génerée automatiquement                                                                                       |
    | RG 03 | L'utilisateur peut avoir plusieurs d'images                                                                          |
    | RG 04 | L'utilisateur peut favoriser plusieurs images                                                                        |
    | RG 05 | Le client peut ajouter qu'un seul like et le retirer                                                                 | 
    | RG 06 | L'utilisateur peut liker plusieurs images                                                                            |
