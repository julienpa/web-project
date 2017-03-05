# Projet web
Informations complètes du projet de programmation web  
Questions : email à Cyrille **et** Julien

## Objectif
Évaluer les capacités à développer une application web avec toutes les technologies front et back (client et serveur) qui ont été vues en cours.

## Cahier des charges
Créer une app de e-commerce avec une interface d'administration des produits et des commandes.

### Fonctionnalitées demandées
#### Clients
- Client pour les utilisteurs
  - Consulter des produits (listes, page produit...)
  - Rechercher de produits / catégories
  - Créer un compte
  - Ajouter des produits à mon panier
  - Passer une commande (**pas de gestion du paiement**, mais envoie d'un email de confirmation)
  - Consulter l'état de mes commandes
  - Modification des informations personnelles (adresse, numéro de téléphone...)
  - Donner une note et écrire un commentaire sur un produit
- Client pour l'administration
  - Se connecter au _back end_ avec autorisation seulement pour les administrateurs
  - Créer des produits (nom, description, catégorie, image, prix...etc.)
  - Faire avancer les étapes de commande (demandée > confirmée > expédiée > livrée)
  - Modérer les notes / commentaires
  - Créer des administrateurs
  
Les clients doivent être fonctionnels sur les principaux navigateurs récents du marché : 

- Firefox 51 et supérieurs
- Chrome 56 et supérieurs
- Edge 14 et supérieurs
- Internet Explorer 11
- Safari 10 et supérieurs

Ceux-ci doivent être dynamiques, c'est à dire que certaines actions devront être réalisables sans rechargement de la page.

#### Serveur
- Apache ou Nginx pour gérer les requêtes entrantes, les URLs, le cache...
- Langage de scripting
- Système de gestion de base de données
- Authentification (Session ou OAuth)
- API REST permettant d'intéragir avec la base de données (à utiliser pour _au moins_ un des 2 clients)

### Technologies utilisées
- Développement : **100% libre**. Le choix et la justification des outils utilisés seront cependant pris en compte :eyes:
- Gestion des sources : [Git](https://git-scm.com/) (cf. section [livrables](#livrables))

## Critères d'évaluation
- Pertinence des **choix techniques**
- Attention particulière portée à la **qualité du code** : HTML, CSS, JS, PHP (ou autre 😉)
- Développement de composants d'interface réutilisables
- Sécurité des données, de l'application et de l'authentification
- Documentation
- Utilisation de git : organisation du repository et des branches, utilisations de PR/MR, fréquence et cohérence des commits
- Répartition du travail dans l'équipe

## Livrables
- Dernière semaine d'avril, probablement le 28/04 avec soutenance le 01/05 (_à confirmer_).
- Votre projet doit être hébergé sur un repository **privé** en ligne, comme [GitLab](https://about.gitlab.com/) ou [Bitbucket](https://bitbucket.org/) (gratuits tous les 2). Il est également possible d'utiliser GitHub gratuitement avec le [student developer pack](https://education.github.com/pack)
- Pensez à inclure au minimum un `README.md` pour expliquer comment est organisé le projet et les étapes basiques permettant de le faire fonctionner
- Soutenance (30-40 minutes) : présentation du projet, des choix techniques et de son déroulement, démo du résultat, questions/réponses

## Bonus (optionels mais appréciés !)
- Qualité de l'UI (interfaces) et de l'UX (ergonomie)
- Faire une démo avec les clients et le serveur sur 2 machines différentes
- Ajout de fonctionnalités que vous jugez utiles ou intéressantes
- Tests unitaires
- Déploiement en ligne : Heroku, DigitalOcean, Scaleway...
- Mise en place de la stack Webpack/Babel/ESLint/Flow (même partiellement, par exemple uniquement Webpack et Babel)
- Utilisation d'un framework ou d'une librairie front-end (Ember, Angular, React, Vue...)
