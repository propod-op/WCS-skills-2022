# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- Comment développer en utilisant un système de *livereloading* (`nodemon` par exemple) ✔️
- La connexion de mon application à une base de données avec et sans ORM/ODM (avec `mongodb` puis `mongoose` par exemple) ❌
- Le développement d'une API REST et GraphQL (avec les packages `express` et `graphql` par exemple) ❌ ~ ✔️
- *Bonus : la manipulation des fichiers système avec `fs` et l'utilisation des streams en NodeJS* ❌

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

npm i nodemon.
créer un serveur node :
------------- index.js -----------------
import express from "express";
const app = express();

app.use(express.json());

async function start(){
  await db.initialize();
  app.listen(4000, () => {
    console.log("server ready");
  });
}

start().catch(console.error);
-----------------------------------------
lancer le serveur :
nodemon index.js


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

- avoir un projet simple incluant un serveur. Une application qui pourrait être utilisée en XP ❌
  créer par exemple une base déportée de celle de shopify.


Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
