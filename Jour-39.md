# Objectifs journaliers

## Lundi 21/10/2019

### Javascript :

- [ ] Comprendre le fonctionnement des `callbacks` (https://javascript.info/callbacks)
- [ ] Comprendre le fonctionnement des `promises` (https://javascript.info/promise-basics)
- [ ] Savoir utiliser le `promises chaining` (https://javascript.info/promise-chaining)

### SQL :

- [x] Savoir ce qu'est une base de données (https://youtu.be/XQ_6G0iCyMQ)
      BDD : collection d’informations organisées afin d’être facilement consultables, gérables et mises à jour.
      Les données sont organisées en lignes, colonnes et tableaux.
      Elles sont indexées pour trouver facilement les informations recherchées à l’aide d’un logiciel informatique. Chaque fois que de nouvelles informations sont ajoutées, les données sont mises à jour, et éventuellement supprimées.
- [x] Savoir ce qu'est `SQL` et une base de données relationnelle (https://youtu.be/MZdO1UbTG4U)
      Système de Gestion des Bases de Données (SGBD) stocke les données
      SQL : langage pour communiquer entre les différents logiciels et le moteur de base de données.
      Base de donnée relationnnelle : l'information est constituée dans des tableaux.

- [x] Découvrir ce qu'est `PostgreSQL` (https://youtu.be/tzbA7VniRpw)
      PostgreSQL : Gestionnaire de base de données. Interface en ligne de commande.
- [x] Installation de `PostgreSQL`
      instalattion linus : sudo apt install postgresql puis verif version psql --version
- [ ] Découvrir le fonctionnement du `REPL` de `PostgreSQL`
- [ ] Création/suppression de comptes utilisateurs
      commande création :
      pour passer du terminal à celui de psql : sudo -s -u postgres
      puis ouvrir psql : psql
      créer un nouvel utilisateur : createuser -d -P name;
      (L’option -d va permettre à notre utilisateur de créer des bases. L’option -P va forcer l’affectation d’un mot de passe qui nous sera demandé de manière interactive.)
      commande suppression: drop user name;
      supprimer un utilisateur :

* [ ] Création de bases de données (https://youtu.be/DvDOU-v822w)
      création base de donnée : CREATE DATABASE name ou createdb name;
* [ ] Suppression de bases de données (https://youtu.be/IWkNbJhn2TM)
      suppression bdd : DROP DATABASE name;
* [ ] Découvrir les rôles dans `PostgreSQL` (https://docs.postgresql.fr/12/user-manag.html)
      Rôles : un utilisateur de la base de données ou un groupe d'utilisateurs de la base de données.
      vérifier les rôles existants : SELECT rolname FROM pg_roles;

### Node.JS :

<<<<<<< HEAD

- Découverte d'`Express.js`
- Installation d'`Express.js`
- # Création d'un hello world personnalisé avec `Express.js` (plusieurs fois)

### Node.JS :

- [ ] Découverte d'`Express.js`
- [ ] Installation d'`Express.js`
- [ ] Création d'un hello world personnalisé avec `Express.js` (plusieurs fois)
  > > > > > > > e6c1519701467cfa7e92312c9c96c8b426cf10af
