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

Mise en place d'une liste de pétitions signés par des utilisateurs authentifiés via google sign in (méthode intégré avec google cloud app engine) et le nombre de signataires affichés. Mais nous ne pouvons pas mettre en place un système de vérification de doubles signatures car nous ne pouvons pas garder les adresses des signataires (car le "@" de l'adresse gène les requètes) et le système d'identification que nous utilisons (id_token) peut changer pour un même utilisateur.

Design gloval de l'application pauvre, car l'implémentation d'un framework bootstrap alourdira l'application (et donc perd tout intérêt d'utiliser mithril qui est un framework léger)

Tous ces problèmes sont connus et cernés, leur correction n'a pas été possible par manque de temps.

