# 420-5DD-HY TP1 Tours de Hanoï

Ce travail pratique compte pour 5% de la note finale du cours

## Règles du jeu

Voir  la définition sur [Wikipédia](https://fr.wikipedia.org/wiki/Tours_de_Hano%C3%AF)

## Mission

Vous devez coder un module Elixir permettant de détailler une solution au jeu des tours de Hanoï pour une hauteur variable de N disques empilés sur le premier poteau en détaillant l'état du jeu à chaque mouvement vers le 3e poteau.

On doit pouvoir invoquer votre programme via la commande suivante :

```elixir
NomÉquipe.hanoi(3) # ici 3 est le nombre de disques utilisé pour le test.

[[1, 2, 3], [], []]
[[2, 3], [], [1]]
[[3], [2], [1]]
[[3], [1, 2], []]
[[], [1,2], [3]]
[[1], [2], [3]]
[[1], [], [2, 3]]
[[], [], [1, 2, 3]]

```
Votre code devra être dans le répertoire "code".

# Barème de correction

* 30% Jeu fonctionnel permettant d'afficher une solution complète
* 30% Affichage correct des états intermédiaires du jeu
* 20% Clarté et simplicité du code
* 20% Respect des [règles de styles Elixir](https://github.com/christopheradams/elixir_style_guide)