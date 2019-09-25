# Objectifs journaliers

## Mercredi 04/09/2019

- [x] Javascript :

  - [x] Comprendre ce que sont les polyfills et leur utilité (https://javascript.info/polyfills)

    - [x] Comprendre la différence entre "transpilation" et "compilation"

      transpilation : action de convertir le Javacript moderne en Javascript standard pour permettre au langage de fonctionner même sur les navigateurs les plus anciens.

      C'est passer d'un langage "developper code" à un autre version de "developper code"
      Compilation : action de convertir un "langage machine" à un "langage developper code"

    - [x] Comprendre l'utilité de Babel

      Babel est un outil de transpilation permetant de ne pas changer le langage d'origine juste en utilisant des polyfills (script qui met à jour ou ajoute de nouvelles fonctions, "comble" le vide et ajoute les implentations manquantes).

  - [x] Découvrir les Objets en JS (https://javascript.info/object)


    - [x] Comprendre le principe de clé/valeur

          l'objet (stocke une collection de clés liés à des valeurs): il se compose de propriétés. une propriété elle-même composé d'une clé (nom ou identité tjrs un string) et de sa valeur (tous types). on peut donc multiplier le nombre de valeurs et en appelant leurs clefs.

    - [x] Comprendre la différence entre un objet et une variable

          un objet est un type de donnée à valeurs multiples stocké grâce à leurs clés différents des autres donnés "primitive" à données uniques (string, number...)
          une variable est un espace mémoire qui stock une seule donnée à la fois.

    - [x] Savoir itérer dans un objet

          Pour itérer dans un objet on utilise la boucle "for...in"

    - [x] Comprendre la copie par référence

          Quand on stocke un objet dans une variable on stocke sa clef et non la valeur elle-même.

    - [x] Savoir copier un objet (cloner)
          il faut créer un nouvel objet,
          puis copier les clés dans le nouvel objet.
          Ex:
          let clone = {}; // the new empty object

          // let's copy all user properties into it
          for (let key in user) {
          clone[key] = user[key];

- [ ] Algo :
  - [x] Ecrire en pseudocode le Bubble Sort (création pure)
  - [ ] Faire valider son code par un "élève" qui joue le rôle de l'ordinateur
