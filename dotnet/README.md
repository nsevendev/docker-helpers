# Dotnet

Environement docker dotnet

## Objectif

- Pouvoir utiliser dotnet sans installer ce dernier en local
- Utilisé principalement pour creer des projets

## Utilisation

- Cloner le projet
- Copier / coller tous les fichiers de ce dossier dans le dossier de votre choix
- renseigner les variables d'environnement dans le fichier `.env`
  - `DOTNET_VERSION` : version à utiliser
  - `NAME_APP` : nom de votre l'application
- Lancer la commande `docker-compose up`
- Lancer la commande `docker exec -it dotnet sh` pour accéder au container
- Vous êtes dans le container, vous pouvez executer toutes les commandes  
  creer des projets, installer des packages, etc...
- Pour quitter le container, tapez `exit`
- Pour stopper le container, tapez `docker-compose down`
- Pensez à nettoyer vos images docker généré
