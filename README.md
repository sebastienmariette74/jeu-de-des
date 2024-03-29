# Projet Jeu de dé - [site](https://sebastienmariette74.github.io/jeu-de-des/)
Projet réalisé au début de ma formation de Développeur Web et Web Mobile chez STUDI.

## Technologies
HTML, CSS, Bootstrap, Javascript

## Détails du projet

### Objectifs

Création d’un petit jeu sur navigateur web à l’aide du DOM.

En fin de prestation, le commanditaire doit recevoir les différents éléments suivants :
- Un jeu fonctionnel
- Une interface lisible qui correspond à la maquette fournie.

Ceci implique plusieurs fonctionnalités globales :

En front-desk (côté client) :
- La possibilité de créer une nouvelle partie
- La possibilité de retenir le score courant
- La possibilité de lancer le dé
- La possibilité d’avoir 2 joueurs

### Règles

Le jeu comprend 2 joueurs sur un seul et même écran.

Chaque joueur possède un score temporaire (ROUND) et un score global (GLOBAL). 

À chaque tour, le joueur a son ROUND initialisé à 0 et peut lancer un dé autant de fois qu'il le souhaite. 

Le résultat d’un lancer est ajouté au ROUND.

Lors de son tour, le joueur peut décider à tout moment de: 
- Cliquer sur l’option “Hold”, qui permet d’envoyer les points du ROUND vers le GLOBAL. Ce sera alors letour de l’autre joueur.
- Lancer le dé. S’il obtient un 1, son score ROUND est perdu et c’est la fin de son tour.

Le premier joueur qui atteint les 100 points gagne le jeu.
