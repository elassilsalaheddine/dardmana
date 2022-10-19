﻿# grails_estia_22_23
PROJET GRAILS LECOINCOIN DE ELASSIL Salah Eddine & HARTI Mohammed

API : Notre API respecte le cahier de charge

Site : Notre site LECOINCOIN propose plusieurs types d'inscription :

-ADMIN : Peut voir tout le contenu, créer tout le contenu, modifier tout le contenu, supprimer tout le contenu.

-MODERATOR : Peut tout voir et tout changer.

- Clients : Peuvent seulement voir les annonces, peuvent seulement créer et modifier/supprimer leurs propres annonces.

Toutes les fonctions (créer, mettre à jour, supprimer, voir) sont disponibles pour l'UTILISATEUR

Comment cela fonctionne-t-il ? Notre page utilisateur est accessible aux admins/modérateurs et affiche une liste d'utilisateurs et leurs données (mdp n'est jamais montré). Elle amène les utilisateurs à créer des pages auxquelles les modérateurs n'ont pas accès. Cependant, MODE et les administrateurs peuvent accéder à la page d'édition.

La page Annonces est accessible à tous les utilisateurs (admins, clients, même ceux qui ne sont pas connectés), elle affiche la liste des annonces et leurs descriptions (prix, titre...). Les admins et les clients peuvent accéder à la page de création ; lorsque les clients créent une annonce, ils n'ont pas besoin de saisir l'auteur de l'annonce, celle-ci apparaîtra automatiquement dans la liste des annonces. Contrairement aux admins qui peuvent sélectionner les utilisateurs souhaités pour créer des annonces. Les pages de modification/suppression sont disponibles pour les administrateurs, les schémas et les clients. Cependant, les clients n'ont pas le droit de modifier/supprimer les annonces qu'ils ne possèdent pas. Les administrateurs et les schémas peuvent modifier n'importe quel affichage. Les administrateurs peuvent supprimer n'importe quelle annonce.
La page d'accueil est accessible via le petit logo Coincoin dans le coin supérieur gauche de chaque page du site.
Sécurité : nous utilisons @secured et tagLibs.

Salah Eddine & Mohammed
