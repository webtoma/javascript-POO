# Exercices JavaScript : Héritage Avancé

Ce projet propose six exercices avancés pour approfondir votre compréhension de l'héritage en JavaScript. Les exercices portent sur des concepts tels que l'héritage de classes, l'appel de méthodes parentes, la surcharge de méthodes et la création de classes abstraites.

## Exercice 1 : Héritage Simple

**Objectif** : Créez une classe enfant qui hérite d'une classe parente.

1. Ouvrez le fichier `exercice1.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe parente `Animal` avec une méthode `manger`.

4. Créez une classe enfant `Chien` qui hérite de `Animal` et ajoute une méthode `aboie`.

## Exercice 2 : Appel de la Méthode Parente

**Objectif** : Apprenez à appeler la méthode parente à partir de la classe enfant.

1. Ouvrez le fichier `exercice2.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Utilisez la classe `Animal` du premier exercice et ajoutez une méthode `dormir` à la classe `Chien`.

4. Dans la méthode `dormir` de la classe `Chien`, appelez la méthode `manger` de la classe parente `Animal`.

## Exercice 3 : Surcharge de Méthode

**Objectif** : Pratiquez la surcharge de méthodes dans une classe enfant.

1. Ouvrez le fichier `exercice3.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Utilisez la classe `Chien` du deuxième exercice et ajoutez une méthode `aboie` qui accepte un argument `fois`.

4. Lorsque la méthode `aboie` est appelée, elle doit afficher "Woof" le nombre de fois spécifié par l'argument `fois`.

## Exercice 4 : Héritage en Profondeur

**Objectif** : Pratiquez l'héritage en profondeur avec plusieurs niveaux de classes.

1. Ouvrez le fichier `exercice4.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe parente `Vehicule` avec une méthode `deplacer`.

4. Créez une classe enfant `Voiture` qui hérite de `Vehicule` et ajoutez une méthode `rouler`.

5. Créez une classe enfant `Moto` qui hérite de `Vehicule` et ajoutez une méthode `accelerer`.

## Exercice 5 : Classes Abstraites

**Objectif** : Apprenez à créer des classes abstraites et à empêcher l'instanciation directe.

1. Ouvrez le fichier `exercice5.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe abstraite `Forme` avec une méthode abstraite `calculerAire`.

4. Créez deux classes enfants `Rectangle` et `Cercle` qui héritent de `Forme` et implémentez la méthode `calculerAire` dans chacune d'elles.

## Exercice 6 : Utilisation de l'Héritage

**Objectif** : Mettez en pratique l'héritage dans un scénario réel.

1. Ouvrez le fichier `exercice6.js` dans votre éditeur de code.

2. Vous trouverez un commentaire indiquant où écrire votre code.

3. Créez une classe parente `Personne` avec des propriétés telles que `nom`, `age` et une méthode `sePresenter`.

4. Créez une classe enfant `Etudiant` qui hérite de `Personne` et ajoutez des propriétés spécifiques à un étudiant, telles que `niveau` et `ecole`.

5. Utilisez les classes `Personne` et `Etudiant` pour créer des instances et appelez les méthodes appropriées pour démontrer l'héritage en action.

Ces exercices vous aideront à maîtriser les concepts avancés de l'héritage en JavaScript. N'hésitez pas à personnaliser les exemples pour approfondir votre compréhension.
