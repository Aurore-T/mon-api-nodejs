![Static Badge](https://img.shields.io/badge/npm-v11.9.0-green)
![Static Badge](https://img.shields.io/badge/node-v25.6.01-green)
![javascript badge](https://img.shields.io/badge/javascript-green)

# Mon api nodejs

# Table des matières

- [DOCUMENT DE SPECIFICATIONS FONCTIONNELLES][1]
- [DOCUMENT TECHNIQUE][1]

[1]: ./functional_documentation.md

## Description du projet
Il s'agit d'une API REST pour la gestion centralisé d'un forum

## A qui s'adresse ce projet ?
Ce projet est destiné à des développeurs qui souhaite avoir un back qui communique avec differentes plateformes.

## Dépendances du projet
```JSON
"dependencies": {
    "bcrypt": "^6.0.0",
    "cors": "^2.8.6",
    "cross-env": "^10.1.0",
    "dotenv": "^17.3.1",
    "express": "^5.2.1",
    "jsonwebtoken": "^9.0.3",
    "mongodb": "^7.1.0",
    "mongoose": "^9.2.3",
    "morgan": "^1.10.1",
    "nodemon": "^3.1.14",
    "redis": "^5.11.0",
    "sanitize-html": "^2.17.1"
},
"devDependencies": {
  "@eslint/js": "^10.0.1",
  "@faker-js/faker": "^10.3.0",
  "eslint": "^10.0.2",
  "globals": "^17.4.0"
}
```

## Instruction d'utilisation
Pour commencer à utiliser l'api, vous devez dans un premier temps cloner le repository.

## Installer le projet

1. Cloner le repository
```BASH
  git clone https://github.com/Aurore-T/mon-api-nodejs.git
  ```
2. Changer le remote
> Prérequis : vous devez créer un repository en amont sur votre github

```BASH
  cd mon-dossier-projet/
  git add remote origin https://github.com/votre-pseudo/votre-repository.git
  git push -u origin nom-branche
   ```

3. Installer les dépendances
```BASH
  npm install
 ```

## Exécuter l'API
```BASH
  npm run start
```
