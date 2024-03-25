![Logo](./Assets/Docker/Docker-Logo.png)

# Docker

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la création d'une image docker ✔️  
Pour créer une image docker on crée un _Dockerfile_.  
Le _Dockerfile_ contient tout ce qui permet de faire fonctionner notre programme:  
    ```
    FROM node:lts-alpine        // Environnement  

    RUN mkdir /app              // Création dossier

    WORKDIR /app                // Racine  

    COPY index.js ./index.js    // Copie des fichiers 

    CMD node index.js           // Exécution de l'application
    ```  
    Ici nous avons créé un _Dockerfile_ mais pour l'exécuter il faut **build** l'image.

    ```
    docker build -t nom-du-fichier .
    ```  
    L'argument -t permet de taguer l'image et de la retrouver plus facilement.  
    Le point à la fin précise que le fichier est dans le répertoire courant.
      
    On peut enfin lancer notre image:
    ```
    docker run nom-du-fichier
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
