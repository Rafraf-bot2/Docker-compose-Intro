# Welcome to this Docker/Docker Compose Project.

## Context
Cet API à été codé dans le but de se faire conteneuriser et orchestrer avec **Docker Compose**.
L'app est disponible <a href="https://openclassrooms.com/fr/courses/2035766-optimisez-votre-deploiement-en-creant-des-conteneurs-avec-docker/7540111-entrainez-vous-en-orchestrant-vos-images-docker-avec-docker-compose" target= "_blank">ici</a>.

## Requirements

- Python3.8 or higher
- Redis server

## How to

```
pip install -r requirements.txt
```

Then you can launch the app with

```
python main.py
```

## App information

- The API is running on port 5000
- The name of the redis service needs to be "redis"
