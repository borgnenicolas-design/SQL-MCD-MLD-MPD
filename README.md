# Exercices

## Explications du MCD

## Modèle Conceptuel de Données

- Pour raccourcir, j'appelle ça la conceptualisation
  - L'image du MCD est intégralement repris sur la solution.
  - J'ai remplacé nom par name et ingredients par recipe car j'ai voulu un peu personnaliser et pour mieux comprendre aussi.

  - La Potion à été fabriqué par des ingrédients
  - Les ingrédients fabriquent une potion.

  - Chaque Table ont des composants communs:
    - id _non nécessaire à ce stade_
    - name _un pour le nom de la potion et un pour un ingrédient_

## La potion devient une fiole si elle n'a pas d'ingrédients !

## Explications du MLD

## Modèle Logique de Données

- Pour faire simple, il s'agit de la transformation du MCD en MLD

### J'ai mis une couleur différente pour chaque exercice

- id is the key -> ..._id ou id_... _clef étrangère pour cette dernière_

- Lors de l'exercice de la MCD elle était écrite en noir, pour la MLD j'ai mis en rouge pour distingué la différence

- Une fois encore j'ai regardé la solution, pour les relations sinon je ne savais pas on extrait le maximum des 2 tables, et on obtient une relation 1-N: OneToMany dans cet exercice

- Ensuite j'ai regardé le cours, on associe l'id de Recipe à Potion "Recipe_id" et de Potion à Recipe "Potion_id"

## A ce stade je n'ai pas regarder l'IA une seule fois !

- Puis à la suite des liaisons entre les deux Tables, on crée une nouvelle table intermédiaire "Recipe_Potion" qui récupère les liaisons de tables "Recipe_id et "Potion_id"
  - J'ai regardé la solution et je me suis rendu compte que je m'étais mélangé les pinceaux é--è

  ## Aucune utilisation d'IA à ce stade non plus
  - Le croquis à été personnalisé bien que reprise depuis la solution n°1 !

## Merci pour le live d'hier qui à été utile !
