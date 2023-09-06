# Exercices JavaScript : Getters et Setters

Ce projet propose dix exercices pour vous aider à comprendre et à pratiquer l'utilisation de getters et de setters en JavaScript. Les exercices portent sur la création de getters et de setters pour les classes, l'accès et la modification de propriétés privées, et l'utilisation de ces méthodes pour la validation et la manipulation des données.

## Exercice 1 : Getter Simple

**Objectif** : Créez un getter simple pour une propriété d'une classe.

1. Ouvrez le fichier `exercice1.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Personne` avec une propriété privée `_nom` et un getter `nom` qui renvoie la valeur de `_nom`.

## Exercice 2 : Setter Simple

**Objectif** : Créez un setter simple pour une propriété d'une classe.

1. Ouvrez le fichier `exercice2.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Utilisez la classe `Personne` du premier exercice et ajoutez un setter `nom` qui permet de modifier la valeur de `_nom`.

## Exercice 3 : Getter et Setter Avancés

**Objectif** : Pratiquez l'utilisation de getters et de setters pour des propriétés privées.

1. Ouvrez le fichier `exercice3.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `CompteBancaire` avec une propriété privée `_solde` et un getter `solde` qui renvoie la valeur de `_solde`.

4. Ajoutez un setter `solde` qui permet de modifier la valeur de `_solde` en vérifiant que la nouvelle valeur est positive.

## Exercice 4 : Validation avec Getters et Setters

**Objectif** : Utilisez des getters et des setters pour valider et manipuler des données.

1. Ouvrez le fichier `exercice4.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Personne` avec une propriété privée `_age` et un getter `age` qui renvoie la valeur de `_age`.

4. Ajoutez un setter `age` qui permet de modifier la valeur de `_age` en vérifiant que la nouvelle valeur est un nombre positif.

## Exercice 5 : Propriété Calculée avec Getter

**Objectif** : Créez une propriété calculée avec un getter.

1. Ouvrez le fichier `exercice5.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Cercle` avec une propriété privée `_rayon` et un getter `aire` qui calcule et renvoie l'aire du cercle en fonction du rayon.

## Exercice 6 : Utilisation de Setters pour des Calculs

**Objectif** : Utilisez des setters pour effectuer des calculs lors de la modification d'une propriété.

1. Ouvrez le fichier `exercice6.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Rectangle` avec des propriétés privées `_longueur` et `_largeur`, ainsi qu'un getter `aire` qui renvoie l'aire du rectangle.

4. Ajoutez des setters pour `longueur` et `largeur` qui permettent de mettre à jour ces propriétés et de recalculer l'aire automatiquement.

## Exercice 7 : Getter pour Données Compliquées

**Objectif** : Créez un getter pour extraire des données complexes.

1. Ouvrez le fichier `exercice7.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Magasin` avec une propriété privée `_produits` qui est un tableau d'objets représentant les produits en vente.

4. Ajoutez un getter `produitsEnPromotion` qui renvoie uniquement les produits en promotion (ceux ayant un prix réduit).

## Exercice 8 : Setter pour Mise à Jour en Batch

**Objectif** : Utilisez un setter pour mettre à jour plusieurs propriétés en une seule opération.

1. Ouvrez le fichier `exercice8.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Personne` avec des propriétés `_nom` et `_prenom`.

4. Ajoutez un setter `miseAJour` qui permet de mettre à jour à la fois le nom et le prénom en une seule opération.

## Exercice 9 : Utilisation de Getters et Setters en dehors de la Classe

**Objectif** : Utilisez des getters et des setters pour accéder et modifier des propriétés privées en dehors de la classe.

1. Ouvrez le fichier `exercice9.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Utilisez la classe `Personne` du huitième exercice et montrez comment utiliser les getters et les setters en dehors de la classe pour accéder et modifier les propriétés `_nom` et `_prenom`.

## Exercice 10 : Validation Complète

**Objectif** : Créez une classe avec des getters et des setters pour valider, accéder et modifier des propriétés complexes.

1. Ouvrez le fichier `exercice10.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe `Commande` avec des propriétés privées `_produit` (le nom du produit), `_quantite` (la quantité commandée) et `_prixUnitaire` (le prix unitaire du produit).

4. Ajoutez des getters et des setters pour chaque propriété afin de valider les données (par exemple, la quantité doit être un nombre positif) et de calculer le montant total de la commande.

Ces exercices vous aideront à comprendre et à pratiquer l'utilisation de getters et de setters en JavaScript pour accéder, valider et manipuler des propriétés privées de classe. Amusez-vous bien !
