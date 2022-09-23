# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ❌
- les spécifités du mot-clef `this` ❌

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

<script>
  // Récupération dans le DOM de l'élément bouton
  let button = document.getElementById("button");

  // définition de la fonction déclenchée par l'event listener 
  let onButtonClick = function() {
    let name = document.getElementById("name").value; //récupération de la valeur de l'attribut "name" d'un input
    let lang = document.getElementById("lang").value; //récupération de la valeur de l'attribut "lang" d'un select
    let greeting;//déclaration de la variable "greeting"
    //structure conditionnelle pour afficher un message différent selon la valeur de "lang"
    if (lang === "es") {
        greeting = "Hola, " + name;
    } else if (lang === "plt") {
        greeting = "Ello-hay, " + name;
    } else {
        greeting = "Heyaz, " + name;
    }
    document.getElementById("message").textContent += greeting;  //insertion du bon message dans le DOM
  };
  // Step 3: Attach event listener to element
  button.addEventListener("click", onButtonClick);//ajout sur le bouton de l'évènement qui déclenche la fonction lors d'un click
  </script>

### Utilisation dans un projet ❌

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌

Description :

## 🌐 J'utilise des ressources

### Titre

- https://learnjavascript.online/app.html
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
- J'ai fait une [présentation](...) ❌ / ✔️

