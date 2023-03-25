# TP_devops
BALDUCCI Victor

Seul pour ce TP j'ai joué le rôle d'intégration manager et le rôle de développeurs. 

PS : Pour mettre à jour ce README au fur et à mesure de ce TP, j'ai choisi de pousser directement sur la branche main sans créer de tag.

## Installation

Clonez ce dépôt de code sur votre ordinateur.
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
- Créez un tag pour fusionner sur la branche principale `main`

## Créer un tag pour la fusion sur la branche principale

Si vous souhaitez fusionner un commit spécifique sur la branche principale (`main`) de votre dépôt Git, vous pouvez créer un tag pour marquer ce commit comme étant prêt pour la fusion. Voici comment procéder :

1.  Positionnez-vous sur la branche de développement (`dev`) et créez un tag pour le commit que vous souhaitez fusionner sur la branche principale. Vous pouvez utiliser la commande suivante pour créer un tag local : `git tag -a v1.0 -m "Description du tag" <commit-id>`
2. Poussez le tag vers le dépôt distant en utilisant la commande suivante : `git push --tags`
3.  Créez une pull request pour fusionner la branche de développement (`dev`) sur la branche principale (`main`).
4.  Dans la description de la pull request, mentionnez le tag que vous avez créé en utilisant la syntaxe suivante : `Merge avec le tag v<numéro de version>`

## Contact

Si vous avez des questions ou des préoccupations, veuillez contacter BALDUCCI Victor (intégration manager).