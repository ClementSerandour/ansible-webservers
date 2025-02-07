# Ansible Role: WebServers

Ce rôle Ansible permet de configurer un serveur web en mettant à jour le cache APT, en installant les services nécessaires et en assurant que ces services sont démarrés et activés.

## Prérequis

Avant d'utiliser ce rôle, assurez-vous que :

- Ansible est installé sur votre machine de gestion.
- Vous avez une machine cible sur laquelle exécuter les tâches.

## Variables

Ce rôle utilise deux variables :

- `packages`: Liste des paquets à installer. 
  packages:
    - apache2
    - mariadb-server

- `services`: liste du nom des services à vérifier le fonctionnement
  services:
  - apache2
  - mariadb
