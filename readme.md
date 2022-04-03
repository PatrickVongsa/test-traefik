# Traefik v2.6 + Docker provider

## What needed ?
- Docker
- Docker-compose

***
## How does it work ?

### First step

Lancer le container pour Traefik :
1. se déplacer dans le dossier traefik
2. lancer la commande docker-compose

```
cd traefik/
docker-compose up -d
```
3. Vérifier si le container est bien lancé :

```
docker ps 
```
4. afficher le tabelau de bord Traefik, se rendre sur traefik.webgo.localhost

***

## Ajouter des applications

Toutes applications ajoutés seront dans le dossier `apps/` (dossier à créer)

*template test :* https://github.com/PatrickVongsa/reactapp-docker

