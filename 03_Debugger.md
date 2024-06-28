# Apprendre JavaScript - Debugger

## Debugger

Le débogueur est un outil qui permet de mettre en pause l'exécution du code à un certain endroit, pour pouvoir inspecter les valeurs des variables, et comprendre ce qui se passe. Il s'agit simplement d'ajouter un mot-clé `debugger` dans le code, à l'endroit où on veut mettre une pause.

```javascript
let prenom = "Jean";
let nom = "Dupont";

// On met une pause ici
debugger;

console.log(`Bonjour ${prenom} ${nom}`);
```

Lorsque le code s'exécute, il s'arrête à la ligne où se trouve le mot-clé `debugger`. On peut alors inspecter les valeurs des variables, et avancer pas à pas dans le code pour comprendre ce qui se passe.

### Utiliser le débogueur

Pour utiliser le débogueur, il faut ouvrir les outils de développement du navigateur web. On peut ouvrir les outils de développement en appuyant sur `F12` ou `Ctrl+Maj+I` (Cmd+Option+I sur Mac). On peut aussi ouvrir les outils de développement en cliquant sur le menu du navigateur, puis sur "Outils de développement".

Dans les outils de développement, on peut ouvrir l'onglet "Sources" pour voir le code JavaScript. On peut cliquer sur le numéro de ligne pour ajouter un point d'arrêt, et mettre le code en pause à cet endroit. On peut aussi cliquer sur le bouton "Step over" pour avancer pas à pas dans le code, ou sur le bouton "Step into" pour entrer dans une fonction.

On peut voir les variables dans la fenêtre "Scope" à droite. On peut aussi ajouter des variables à la fenêtre "Watch" pour les suivre plus facilement.
