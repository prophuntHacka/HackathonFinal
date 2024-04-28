# Hunt the Woka

Le Prop Hunt est un mode de jeu multijoueur où deux équipes s'affrontent : les Chasseurs et les Props.

Les Chasseurs traquent et éliminent les Props, qui se transforment en objets du décor pour se camoufler. Le jeu se déroule en une manche, et la stratégie est essentielle pour survivre ou pour débusquer ses adversaires.

## Features

1. **hideNameAndStatus (code source) (Stéphane et Kilyan)** : Cette fonctionnalité permet de masquer le nom et le statut des joueurs pendant le jeu. Cela peut être crucial dans le Prop Hunt pour maintenir le mystère et la difficulté pour les Chasseurs de repérer les Props.

2. **setPlayerTexture (code source) (Stéphane et Kilyan)** : Cette fonctionnalité permet de définir la texture ou l'apparence des joueurs pendant le jeu. Dans le contexte du Prop Hunt, cela pourrait être utilisé pour permettre aux Props de choisir leur apparence lorsqu'ils se transforment en objets du décor.

3. **Timer (Hugo)** : Le timer est une fonctionnalité qui compte le temps écoulé pendant le jeu. Dans le Prop Hunt, un timer permet de définir la durée de chaque manche et pour créer un défi contre-la-montre pour les Chasseurs et les Props.

4. **Gestion de rôle (Hugo)** : Cette fonctionnalité gère les rôles des joueurs dans le jeu. Dans le Prop Hunt, elle détermine si un joueur est un Chasseur ou un Prop, et peut également affecter les capacités ou les outils disponibles pour chaque équipe (pas développer).

5. **Comptage des joueurs dans la room (Hugo)** : Cette fonctionnalité compte le nombre de joueurs présents dans la salle de jeu. C'est important pour s'assurer qu'il y a un nombre suffisant de joueurs pour démarrer une partie équilibrée.

6. **Interactions joueurs et environnement (Hugo)** : Cette fonctionnalité permet aux joueurs d'interagir avec l'environnement du jeu. Dans le Prop Hunt, cela inclut la possibilités de se déplacer en tant que Props.

7. **Création de maps (Jean-Pierre et Hugo)** : Cette fonctionnalité concerne la conception et la création de cartes de jeu. Dans le Prop Hunt, elle implique la création d'environnements détaillés et variés, avec une disposition stratégique des objets du décor pour offrir des possibilités de camouflage aux Props et des défis de recherche aux Chasseurs.

## Requirements

Node.js version >=17

## Installation

With npm installed (comes with [node](https://nodejs.org/en/)), run the following commands into a terminal in the root directory of this project:

```shell
npm install
npm run dev
```

## Test production map

You can test the optimized map as it will be in production:
```sh
npm run build
npm run prod
```

## Licenses

This project contains multiple licenses as follows:

* [Code license](./LICENSE.code) *(all files except those for other licenses)*
* [Map license](./LICENSE.map) *(`map.tmj` and the map visual as well)*
* [Assets license](./LICENSE.assets) *(the files inside the `src/assets/` folder)*


