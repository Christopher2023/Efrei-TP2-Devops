# Efrei-TP2-Devops

## Fichier yaml
1. Après de nombreuses recherches faites sur internet, j'ai pu créer le fichier. Au début j'ai eu des problèmes que vous m'avez d'ailleurs c'est que sur le nom des steps je mettais le nom de dossier plutôt. Nous avons chang" ça ensemble et ça a fonctionné. Pour tester j'ai d'abord essayer avec mon code du TP1.

## Code Python
1. J'ai d'abord copié le code python du TP précédent
2. Pour créer l'API j'ai utilisé la librairie **hug** car dans un précédent cours nous l'avons utilisé 
3. Ensuite j'ai adapté le code en fonction du fonctionnement de l'API et la commande à taper au final

## Configuration de l'image
1. D'abord, j'ai créé le Dockerfile et y ai configuré mon image. Pour ce faire, adapter mon code en y ajoutant dans le **RUN** du Dockerfile la librairie hug et la version.
2. Enfin, j'ai modifié le **CMD** afin de lancer hug lorsque je run mon docker
3. J'ai rencontré un problème majeur, et ce lorsque j'utilisais le run pour lancer mon docker : ma variable d'environnement n'était pas prise en compte. J'y ai réfléchi pendant longtemps,  j'ai même contacté un ami de classe et on a pas pu résoudre ce problèm mais ensuite il a proposé d'entrer dans le docker pour voir ce qui se passait, ce qu'on a fait. Là nous nous sommes rendus compte que tout fonctionnait très bien depuis le départ, mais pour une raison que j'ignore sur mon ordinateur ça ne fonctionnait pas. Je lui ai envoyé le code pour tester sur sa machine et tout a bien fonctionné donc c'était bel et bien mon ordinateur qui posait problème.
