***************************************************
* Application react web documentation Lucas barq  *
***************************************************

## Liste des commandes utilisables

Premièrement afin d'utiliser l'application veuillez ouvrir un terminal et vous rendre dans le répertoire de l'application 
Une fois dans le repertoire : 

### `npm start`

Permet de lancer l'application en mode développement sur un server local accessible a l'adresse : 
http://localhost:3000 dans votre navigateur.

Cette vue permet de suivre le dévelppement de votre application grâce au reporting des erreurs dans la console. De plus en rafraichissant la page vous pourrez voir les changements effectués. 

### `npm test`

Permet de lancer une procédure de test interractifs. 

### `npm run build static`

Permet de build l'application pour la mise en production, l'application build ce trouve dans le dossier build accessible depuis la racine de l'application. 

### containerisation 

Le lancement de l'applicatio dans un container docker peut ce faire via un terminal en lançant la commande suivante :

`docker-compose -f docker-compose.dev.yml up`

mais n'est pas obligatoire