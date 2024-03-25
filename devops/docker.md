![Logo](./Assets/Docker/Docker-Logo.png)

# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️  
Pour créer une image docker on crée un _Dockerfile_.  
Le _Dockerfile_ contient tout ce qui permet de faire fonctionner notre programme:  
```
// Environnement pour faire fonctionner notre app 
FROM node:lts-alpine  

// On crée le dossier qui va contenir notre app
RUN mkdir /app

// On se place dans le dossier 
WORKDIR /app

// On copie les fichiers nécessaires au bon fonctionnement de l'app. 
COPY index.js ./index.js

// Enfin on exécute la commande qui lance notre app
CMD node index.js
```

- l'éxécution d'un container ❌ / ✔️
- l'orchestration de containers avec docker-compose ❌ / ✔️


## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
