# led-strip
Controle de bandeaux de LED

Le but de ce script est de controler la couleur d'un bandeau de LED RGB via un raspberry pi, et ce depuis une page web accessible sur un smartphone.

Le contrôle du bandeau se fait via un script en python prenant pour argument le code RGB de la couleur à afficher (3 arguments entre 0 et 225). Je souhaite ajouter un contrôle de la luminosité également via un quatrieme argument.

L'idée est d'utiliser une page html pour choisir la couleur sur un nuancier, la transformer en code RGB, transmettre ces données vers une page PHP qui execute le script python et allume le bandeau de la couleur demandée.

Pour l'instant fonctionne:

La page html du nuancier (allègrement volée ici: http://johndyer.name/photoshop-like-javascript-color-picker/)

le script python prenant pour argument le code RGB de la couleur.


Objectifs:

transformer la page du nuancier en un formulaire qui envoi le code RGB à la page PHP d'execution du script

Faire exectuer le script python par la page PHP, avec les bons arguments.
