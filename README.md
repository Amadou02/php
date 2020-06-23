# Exercices Bonus PHP

## Super-globales et Formulaires

### Exercice 1

Créer un formulaire d'inscription dans votre page d'accueil <span style="color: red">**index.php**</span> avec les champs suivant :

<span style="color: red">**Civilité**</span> de type radio

<span style="color: red">**prénom, nom**</span> de type texte

<span style="color: red">**Date de naissance**</span> de type date

<span style="color: red">**Email**</span> de type email

<span style="color: red">**Mot de passe**</span> de type texte

<span style="color: red">**confirmation du mot de passe**</span> de type texte

<span style="color: red">**conditions générale d'utilisation**</span> de type checkbox

Le traitement du formulaire doit se faire dans la même page.

A la validation du formulaire, afficher le formulaire et les messages d'erreurs s'il y'en a, sinon créer un cookie et stocker y les données de l'utilisateur.

## Exercice 2

Dans une page <span style="color: red">**user.php**</span>, vérifier que le cookie utilisateur a bien été déposé et afficher les données de l'utilisateur.

_La date de naissance doit être affichée en français_

## Exercice 3

Créer un formulaire de connexion dans une page <span style="color: red">**login.php**</span>

A la validation du formulaire, créer une session utilisateur avec son login et un statut loggedIn.

Dans chaque page, si l'utilisateur est connecté, afficher la première lettre de son pseudo dans la barre de navigation.

## Exercice 4

Créer un page administration, elle ne doit être accessible que pour un utilisateur connecté.

## Exercice 5

Ajouter un bouton déconnexion dans la barre de navigation de l'utilisateur lorsqu'il est connecté. Au clique sur ce bouton, mettre fin à sa session.
