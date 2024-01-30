# EasyBee-Android
Atelier Pro visant à créer une application Android Java pour mettre en relation des particuliers avec des apiculteurs.
Le particulier doit juste saisir son nom, son prénom et cliquer sur un bouton de validation capturant ses coordonnées GPS et son identification dans une base de données lorsqu'ils ont trouvés un essaim.
Les apiculteurs après une authentification ont accès à une liste des différents essaims localisés dans la base de données, ils peuvent n'en prendre qu'un et ont jusqu'à 3 heures pour le récupérer et être validé par le client (si au cours du trajet, le mobile voit à être interrompu, l'apiculteur doit juste se reconnecter et sera directement mis sur l'essaim en cours avec le timer toujours en cours).
Le code utilise également du php pour exécuter des requêtes SQL visant à modifier la base de données en fonction des données reçues des requêtes POST HTTP de l'application Java conçu sous Android Studio.
