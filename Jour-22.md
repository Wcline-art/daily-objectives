# Objectifs journaliers

## Lundi 09/09/2019

- [ ] Javascript :

  - [ ] Comprendre le système de `Garbage Collection` (https://javascript.info/garbage-collection)
    - [ ] Comprendre son utilité, les conditions de son déclenchement, sa manipulation
  - [ ] Comprendre le `this` en Javascript (https://javascript.info/object-methods)

        L'objet est composée de propriétés dont la valeur peut-être une fonction, elle est appelée méthode.
        On utilise des expressions de fonction.
        Syntaxe méthode : nom de l'objet.nom de la méthode()
        This : raccourci, il permet de remplacer le nom de l'objet dans une méthode.
        Ex : let user ={
                name = "Céline";
                age = 30;

                sayHi(){
                  alert(this.name);
                 };
        }
        user.sayHi(); // Céline

* [ ] Découvrir la conversion d'objets en primitives (https://javascript.info/object-toprimitive)
