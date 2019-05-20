# TinyPet TOMAS NYUNTING BAIL

Ici notre dépôt pour notre projet Cloud sur **Google App Engine**.

## Le lien de notre site : 
https://cloudtomasnyuntingbail.appspot.com/

## Le lien de notre explorateur d'API : 
https://cloudtomasnyuntingbail.appspot.com/_ah/api/explorer

## Nos fonctionnalités
Notre site permet de se consulter des pétitions, en créer, en signer et se connecter avec son compte Google.

## Avant d'utiliser
Avant de pouvoir signer une pétition, il faut absolument que vous soyez connecté sur votre compte Google.

## Nos difficultés
Plusieurs difficultés sur le projet : 

Mise en place du compteur du nombre de voix par pétitions, nous n'avons pas réussi à implémenter une fonction de mise à jour dans l'API.

Mise en place de la liste des pétitions que j'ai signé, car l'API ne parvient pas à trier sur l'élément d'identification que nous lui passons (une adresse mail, le @ fait planter la requête). Pourtant quand on regarde dans l'API la fonction listAllSignatures, on voit bien les pétitions signées.

Nous n'avons pas réussi à mettre en place la vérification d'une double signature, pour les mêmes problèmes qu'évoqués au dessus.

Design global de l'application pauvre, dû à une mauvaise prise en main de framework mithril.js.

Tous ces problèmes sont connus et cernés, leur correction n'a pas été possible par manque de temps.

