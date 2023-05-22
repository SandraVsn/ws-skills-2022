# GraphQL

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- la différence entre REST et GraphQL ✔️
REST est l'architecture de conception d'API la plus répendue. Elle utilise les verbes HTTP (ex: GET, POST, PUT et DELETE) pour manipuler les ressources. Chaque endpoint REST est spécifique à une ressource, et le client récupère toutes les données liées à cette ressource, même si elles ne sont pas nécessaires. 
GraphQL n'expose généralement qu'un seul endpoint et c'est le corps de la requête qui contient la structure de la requête ou de la mutation qui permet au client de spécifier exactement les données dont il a besoin. Le client peut donc demander des champs spécifiques, effectuer des requêtes complexes avec des relations et obtenir une réponse structurée contenant uniquement les données demandées.

- les besoins auxquels répond GraphQL ✔️
    * Réduction des allers-retours (over-fetching/under-fetching) : GraphQL permet de récupérer uniquement les données nécessaires en une seule requête, évitant ainsi le surchargement de données inutiles ou le besoin de faire plusieurs requêtes.
    * Flexibilité dans les requêtes : Les clients GraphQL ont la possibilité de définir les champs, les relations et les données dont ils ont besoin, ce qui permet d'obtenir une réponse personnalisée et optimisée.
    * Évolution des APIs sans rupture : Grâce au typage fort du schéma et à la flexibilité de GraphQL, il est possible d'ajouter de nouvelles fonctionnalités ou de nouveaux champs à l'API sans impacter les clients existants. Cela permet une évolution progressive de l'API tout en assurant la compatibilité avec les clients existants.

- la définition d'un schéma ✔️
Un schéma GraphQL définit la structure, les types de données et les relations entre les types dans une API GraphQL. Il agit comme un contrat entre le serveur et le client. Le schéma est écrit en langage SDL (Schema Definition Language) et comprend des types d'objets, des champs, des relations et des directives. Il permet au client de comprendre quelles données sont disponibles et quelles requêtes peuvent être effectuées.

- Query ✔️
Une Query en GraphQL est une opération utilisée pour récupérer des données du serveur. Elle correspond généralement à une requête GET dans REST. Une requête GraphQL spécifie les champs et les relations que le client souhaite récupérer et la structure des données renvoyées correspond exactement à la structure de la requête.

- Mutation ✔️
Une Mutation en GraphQL est une opération utilisée pour modifier les données côté serveur. Elle correspond aux requêtes POST, PUT, DELETE de REST. Contrairement à une Query, une Mutation permet de modifier l'état du système en ajoutant, mettant à jour ou supprimant des données.

- Subscription ✔️
Les Subscriptions en GraphQL sont utilisées pour permettre aux clients de s'abonner à des événements en temps réel. Contrairement aux requêtes Query et Mutation qui renvoient des résultats une fois, les Subscriptions maintiennent une connexion continue entre le client et le serveur, permettant aux clients de recevoir des mises à jour instantanées lorsque des événements spécifiques se produisent.


## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
