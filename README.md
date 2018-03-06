# Projet web
Informations complètes du projet de programmation web  
Questions : email à Cyrille + Alexandre + Julien, ou #projetweb sur Slack

## Objectif
Évaluer les capacités à développer une application web avec toutes les technologies front
et back (client et serveur) qui ont été vues en cours.

## Cahier des charges
Créer une app de type _TODO List_ avec une gestion de tâches et des utilisteurs.

### Fonctionnalitées demandées
#### Client
- Pré-requis technique
  - Le client doit être une app JS frontend qui tourne dans le navigateur
  - Le client doit être fonctionnel sur les principaux navigateurs récents du marché
  (Firefox, Chrome, Edge) 
- Fonctionnalités minimales
  - Créer un compte utilisateur (email, nom d'utilisateur, mot de passe, date de naissance, photo)
  - Connexion et déconnexion à l'app
  - Modifier son profil
  - Créer, modifier et supprimer des listes
  - Créer, modifier et supprimer des tâches
  - Créer et supprimer des sous-tâches
  - Changer le statut d'une tâche (todo / completée)
- Fonctionnalités bonus
  - Envoie d'email pour les invitations et les mises à jour de statut
  - Inviter des utilisateurs à collaborer sur une liste
  - Définir la progression d'une tâche princiaple en fonction de ses sous-tâches

#### Serveur
- Créer un serveur d'API avec toutes les routes et fonctionnalités qu'il est nécessaire
d'exposer
- Permettre l'authentification des clients
- Utiliser au minimum Node et PostgreSQL

Bonus
- Authentification par token (Oauth)

### Technologies utilisées
- Pour le développement, vous pouvez utiliser n'importe quelles solutions techniques (en
tenant compte des pré-requis ci-dessus). Le choix et la justification des outils
utilisés seront cependant pris en compte :eyes:
- Gestion des sources : [Git](https://git-scm.com/) (cf. section [livrables](#livrables))

## Critères d'évaluation
- Pertinence des **choix techniques**
- Attention particulière portée à la **qualité du code** : HTML, CSS, JS
- Développement de composants d'interface réutilisables
- Sécurité des données, de l'application et de l'authentification
- Documentation
- Utilisation de git : organisation du repository et des branches, utilisations de PR/MR,
fréquence et cohérence des commits
- Répartition du travail dans l'équipe
- Clarté et qualité de la présentation du projet (générale, fonctionnelle et technique)

## Livrables
- Projet à envoyer par email la dernière semaine d'avril, date exacte à confirmer.
- Le projet doit être hébergé sur un repository **privé** en ligne, comme [GitLab](https://about.gitlab.com/) ou [Bitbucket](https://bitbucket.org/) (gratuits tous les 2). Il est également possible d'utiliser GitHub gratuitement avec le [student developer pack](https://education.github.com/pack)
- Invitez les 3 enseignants comme _reporters_ ou _contributeurs_ de votre projet
- Pensez à inclure au minimum un `README.md` pour expliquer comment est organisé le projet et les étapes basiques permettant de le faire fonctionner
- Soutenance (25-30 minutes) : présentation du projet, des choix techniques et de son déroulement, démo du résultat, questions/réponses

## Bonus (optionels mais appréciés !)
- Qualité de l'UI (interfaces) et de l'UX (ergonomie)
- Faire une démo avec les clients et le serveur sur 2 machines différentes
- Ajout de fonctionnalités que vous jugez utiles ou intéressantes
- Tests unitaires
- Déploiement en ligne : Heroku, DigitalOcean, Scaleway...
- Mise en place de la stack Webpack/Babel/ESLint/Flow (même partiellement, par exemple uniquement Webpack et Babel)
- Utilisation d'un framework ou d'une librairie front-end (Ember, Angular, React, Vue...)
