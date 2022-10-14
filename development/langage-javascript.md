# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage  ✔️
- les normes `ecmascript`  ✔️
- l'utilisation de l'`asynchrone`  ✔️
- les spécifités du mot-clef `this`  ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté  ✔️
`fonction modofier un tableau hexa a partir d'un tableau de byte`
```javascript
function toggleByte(arr1, arr2) {
  output = [];
  for (let i = 0; i < arr1.length; i++) {
    if (arr2[i] == 0) {
      if (arr1[i] == 255) {
        output.push(254);
      } else if (arr1[i] % 2 == 1) {
        output.push(arr1[i] + 1);
      } else {
        output.push(arr1[i]);
      }
    }
    if (arr2[i] == 1) {
      if (arr1[i] % 2 == 0) {
        output.push(arr1[i] + 1);
      } else {
        output.push(arr1[i]);
      }
    }
  }
  console.log(output);
}
toggleByte([12, 11, 255], [1, 1, 0]);
```

### Utilisation dans un projet ✔️
- animation du dé dans mon projet de jeu de société
[lien github](https://github.com/WildCodeSchool/2022-03-php-remote-1283-montbeliard-cite-libre/blob/dev/assets/diceanimation.js)(...)

Description :

### J'ai utilisé ce langage en production  ✔️
- Modal en JS, librairie pour les confettis de la victoire, animation dé, utilisateur de stimulusJS avec symfony.
[lien du projet](https://github.com/WildCodeSchool/2022-03-php-remote-1283-montbeliard-cite-libre)(...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

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
- J'ai fait une [présentation](...) ❌ / ✔️

