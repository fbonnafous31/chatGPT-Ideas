npm c'est quoi ? 

npm init -y

Wrote to /home/bonnafous/projets/sideProjects/chatGPT/Ideas/package.json:

{
  "name": "Ideas",
  "version": "1.0.0",
  "description": "npm init -y",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}

Projet TypeScript

Compilation avec ViteJS

Installation de Vite et TypeScript

npm install vite typescript --save-dev


Installation du package picocss

npm install @picocss/pico


Modification du package package.json

  "scripts": {
    "start": "vite dev",
    "build": "vite build",


Modification du style.css

@import url("@picocss/pico");


npm start

VITE v4.2.1  ready in 213 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help


https://platform.openai.com/docs/api-reference

https://platform.openai.com/docs/api-reference/completions

Clé API
https://platform.openai.com/docs/api-reference/completions


npm run buid
création d'un dossier dist contenant les fichiers exécutables (TS traduit en JS + CSS minifiés)


Gestion des variables d'environnements
https://vitejs.dev/guide/env-and-mode.html

Création d'un fichier d'environnement à la racine du site (.env.local, ignore by git)
Définition de la variable d'environnement VITE
Utilisation de la variable d'environnement import.meta.env.VITE_