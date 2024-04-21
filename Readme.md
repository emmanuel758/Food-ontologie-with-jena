# FOOD ONTOLOGY - DEPLOY ANGULAR APP AND JENA FUSEKI SERVER WITH DOCKER COMPOSE

## REQUIREMENTS

- docker compose

## INSTALLATION

Dans le dossier LEUNA_20U2698 se trouve 2 fichiers

- docker-compose.yml qui specifie l'emplacement des images docker pour l'application angular et pour jena (executer jena avec des donnes
  pré - enregistrées est unpeu plus complexe)
- handon3.owl qui represente la base de donnés a deployer sur jena

Suivre les etapes suivantes pour lancer les programmes:

- Ouvrir le dossier LEUNA_20U2698 dans le terminal
- se rassurer que les adresse localhost:3030 et localhost:4200 ne sont pas occupé par d'autre applications
- saisir docker compose up 
- Ouvrir le navigateur et aller a l'adresse --localhost:3030-- 
- au niveau du dataset HANDOND3 cliquer sur add data
- importer le fichier handon3.owl et valider
- Se rassuerer que le endpoint dans jena est /HANDON3/query
- Ouvrir localhost:4200 et tester !
