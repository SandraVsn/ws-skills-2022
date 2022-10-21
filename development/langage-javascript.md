# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
Langage dont le typage est faible et dynamique 
Il existe différents types de données : string, number, boolean, null, undefined, array, object
Utilisation de fonctions natives (math, map, parseInt ...)
Creations de fonctions, utilisation de callbacks

- les normes `ecmascript` ✔️
Elles permettent la standardisation des langages de script 

- l'utilisation de l'`asynchrone` ✔️
Permet au programme de démarrer une tâche dont on ne connait pas la durée d'exécution (plus ou moins longue) et de continuer à réagir à d'autres évènements pendant l'éxecution de la première tâche. Une fois la tâche terminée le programme reçoit le résultat mais cette attente n'aura pas bloqué la suite du code.
.then/.catch
async/await avec des blocs try/catch/(finally)

- les spécifités du mot-clef `this` ❌ / ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

Appel à l'API du gouvernement pour récupérer des adresses

```javascript
document.querySelector("#adresse").addEventListener("input", (event) => {
  console.log(event.target.value);
  let url = `https://api-adresse.data.gouv.fr/search/?q=${event.target.value.replace(
    / /g,
    "+"
  )}&limit=5`;

  fetch(url)
    .then((response) => {
      if (response.ok) {
        return response.json();
      }
    })
    .then((datas) => {
      let affichage = `<datalist id="listeAdresses">`;
      for (let data of datas.features) {
        affichage += `<option value="${data.properties.label}">`;
      }
      affichage += "</datalist>";
      document.querySelector("#adresses").innerHTML = affichage;
    })
    .catch((err) => {
      console.log("erreur : " + err);
    });
});
```

### Utilisation dans un projet ❌ / ✔️

[lien github[](...)](https://github.com/SandraVsn/Argonautes-WCS)

Description : Récupération de données et affichage dynamique. 

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ✔️

Description : utilisation de Javascript en front avec le framework vueJS et en back avec le framework NestJS 

## 🌐 J'utilise des ressources

### Documentations THIS 

- [lien](https://dmitripavlutin.com/gentle-explanation-of-this-in-javascript/)
- article proposé par mdn pour comprendre this en javascript

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:
Algorythmie 

Plan d'action : (à valider par le formateur)

- Utiliser codinGames ❌ / ✔️
- Utiliser codeWars ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

