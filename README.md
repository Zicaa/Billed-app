## L'architecture du projet :
Ce projet, dit frontend, est connecté à un service API backend que vous devez aussi lancer en local.

## Organiser son espace de travail :
Cloner le repository via :

```git clone https://github.com/Zicaa/Billed-app.git```

Lancer le backend :

```
cd Billed-app-FR-Back
npm install
npm start
```

L'API du backend sera alors accessible en local via l'URL :
```
http://localhost:5678
```

Lancer le frontend :

```
cd Billed-app-FR-Front
npm install
npm install -g live-server
npm start
```

Le site est accessible en local via l'URL :
```
http://127.0.0.1:8080
```

## Comment lancer tous les tests en local avec Jest ?

```
$ npm run test
```

## Comment lancer un seul test ?

Installez jest-cli :

```
npm i -g jest-cli
jest src/__tests__/your_test_file.js
```

## Comment voir la couverture de test ?

`http://127.0.0.1:8080/coverage/lcov-report/`

## Comptes et utilisateurs :

Vous pouvez vous connecter en utilisant les comptes:

### administrateur : 
```
utilisateur : admin@test.tld 
mot de passe : admin
```
### employé :
```
utilisateur : employee@test.tld
mot de passe : employee
```
