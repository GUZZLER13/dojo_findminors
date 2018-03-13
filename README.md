# DOJO - Retrouver des personnes mineures

Le but de ce dojo va être de créer une fonction qui parcours un tableau à la recherche de toutes les personnes mineures. La fonction retournera le nombre de personnes mineures trouvées.

# Installation

* Cloner le projet dans votre espace de travail

    `git clone dojo_findminors`

* Installer le projet en local

    `npm install`
    
# Fonctionnement du projet

Le fichier utilisé pour créer la classe contenant la méthode est **users.js**
Le fichier utilisé pour tester la méthode est **users-spec.js**

Le principe va être de créer une méthode *findMinors* parcourant une liste d'utilisateurs passés en paramètre, qui retournera le nombre de personnes mineures trouvées.

Le type d'objet *User* aura la syntaxe suivante : `{ nom: 'Alex', age: 29 }`

La fonction *findMinors* va parcourir la liste avec une boucle *for* et incrémenter une variable initialisé à 0 dès qu'un utilisateur qui aura un âge inférieur à 18 sera trouvé.

La fonction *findMinors_filter* va filtrer la liste et retourner la longueur de ce tableau filtré.

# Lancer les tests

_Les tests unitaires seront fait avec Karma/Jasmine_

* Pour lancer les tests, utiliser la commande suivante : 

    `npm test`
