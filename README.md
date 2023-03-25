# TP_devops
## Installation

Clonez ce dépôt de code sur votre ordinateur.

Assurez-vous que vous avez les versions les plus récentes de Node.js et npm installées.

Dans le répertoire du projet, exécutez la commande `npm install` pour installer toutes les dépendances du projet.

## Utilisation

Pour lancer l'application en mode développement, exécutez la commande `npm run dev`. Cela lancera l'application sur le port 3000 et rechargera automatiquement le serveur lors des changements de code.
 
Pour lancer l'application en mode production, exécutez la commande `npm start`. Cela lancera l'application sur le port 8080.

## Processus de développement

Ce dépôt utilise une méthode de gestion de branches appelée "Git flow" qui permet de séparer le développement et la production et de faciliter la collaboration entre les membres de l'équipe.

Le dépôt contient deux branches principales : main et dev. La branche main est utilisée pour la production, c'est-à-dire la version stable et déployée de l'application. La branche dev est utilisée pour le développement, c'est-à-dire la branche principale pour la collaboration des développeurs.

Dans ce processus de travail, un intégrateur (appelé intégration manager) est en charge de valider les merge request de la branche dev vers la branche main. Ainsi, le développeur crée une nouvelle branche pour chaque fonctionnalité qu'il implémente, travaille sur cette branche et la fusionne ensuite dans la branche dev une fois qu'il a terminé. Il crée ensuite une merge request pour demander à l'intégration manager de valider la fusion de sa branche dans la branche main.

Cela permet de s'assurer que toutes les fonctionnalités sont testées et validées avant d'être déployées en production. De plus, cela permet de séparer les développements en cours de la version stable en production, ce qui permet d'isoler les bugs et les problèmes éventuels.

## Contribuer

Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes suivantes :
- Créez une nouvelle branche pour votre fonctionnalité à partir de la branche dev.
- Implémentez votre fonctionnalité et testez-la.
- Fusionnez votre branche dans la branche dev.
- Créez une merge request pour demander à l'intégration manager de valider la fusion de votre branche dans la branche main.

## Contact

Si vous avez des questions ou des préoccupations, veuillez contacter l'intégration manager.