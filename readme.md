# API REST avec Express et Mongo

Ceci est une API REST avec une BDD no sql Mongo développée pour l'écriture d'un tutoriel le blog ci-dessous.

- [https://etienner.github.io/une-api-rest-avec-express-et-mongo-preparatifs](Partie 1 : Préparatifs)
- [https://etienner.github.io/une-api-rest-avec-express-et-mongo-developpement](Partie 2 : Développement)
- [https://etienner.github.io/une-api-rest-avec-express-et-mongo-tests-automatises](Partie 3 : Tests automatisés)

## Installation

### Prérequis

Vérification de Node et NPM sur la machine.

`node -v && npm -v`

Vérification présence de Docker Docker Compose sur la machine.

`docker version && docker-compose version`

### Lancement de l'API

Clonez ce projet puis installez les paquets dans le dossier "services/api" avec la commande `npm i`.

Lancement de l'API depuis la racine du projet.

`docker-compose up -d`

Si tout va bien, [http://localhost:3000](http://localhost:3000) est accessible.

Plus d'informations : [https://etienner.github.io/une-api-rest-avec-express-et-mongo-preparatifs](Partie 1 : Préparatifs)

### Test unitaires

Lancement des tests depuis la racine du projet.

`docker-compose -f docker-compose.test.yml`

Plus d'informations : [https://etienner.github.io/une-api-rest-avec-express-et-mongo-tests-automatises](Partie 3 : Tests automatisés)
