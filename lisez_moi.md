# Projet de Génération de Musique Procédurale

## Description

Ce projet concerne la génération de musique de manière procédurale. Il utilise MetaSounds pour créer des bandes sonores uniques et dynamiques. La musique générée peut s'adapter à diverses situations et humeurs, ce qui la rend idéale pour les jeux vidéo, les films et d'autres applications multimédia.

### Installation

1. Clonez ce dépôt: `git clone https://github.com/khial-lacerenza/procedural_music.git`
2. Ouvrez le projet avec Unreal Engine 5.3.2

### Utilisation

Pour commencer à générer de la musique, appuyez sur play dans Unreal Engine

### Caractéristiques

- Génération de musique dynamique avec MetaSounds d'Unreal Engine
- Paramètres personnalisables pour la génération de musique

## Explications & Objectifs

### Explications

Nous avons commencer par explorer les outils proposé par Unreal Engine et Unity pour déterminer ce que nous allions pouvoir faire dans le cadre de ce projet.

Unreal Engine propose un outil (MetaSounds) qui permet de manipuler differentes formes d'ondes, de créer des formes d'ondes facilement, mais aussi de mixer des signaux audio pour les utiliser en sortie.

Ce module propose tout un panel de fonctions très utile dans le domaine de la création musicale, il permet de créer facilement des LFO (Low Frequency Oscillator) mais aussi d'autres type de filtres, il y'a des fonction de trigger qui permettent de lancer des evenement de manière repeté, etc.

A ces outils s'ajoute les fonctions mathématique que propose Unreal en tant que moteur de jeux qui permettent de jouer avec les paramètres des filtres et des autres modules dont j'ai parlé plus haut.

Il y'a notemment une fonction Random qui permet de générer des nombres aléatoire dans une certaine intervale qui a été très utile pour moduler la fréquence de certains oscillateur que nous avons utilisé.

