#Auction:
1 ere étape: composer install
2 eme étape : en e dérige sur le ficheier .env est en change les variables :
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=Auction
DB_USERNAME=root
DB_PASSWORD=
3 éme étape  :runner la commande php artisan migrate
4 éme étape runner la commande php artisan db:seed(pour remplir la base de données automatiquement)
5 éme étape :runner la commande php artisan storage:link (pour que vous pouvez vois les photos des aticles)
6 éme étape :démmarer le serveur par php artisan serve;
#Démonstration:
Projet de démonstration basé sur l'authentification Breeze,
avec des mises à jour des enchères en temps réel et des ventes de lots automatiques après l'expiration du délai.
#fonctionnalités:
Le projet a les caractéristiques suivantes :
- Enregistrement et authentification des utilisateurs.
- Rôles et autorisations Spatie.
- Panneau d'administration pour la gestion des utilisateurs et des lots.
- Téléchargement d'images de lots.
- Mise à jour des enchères via Socket.io.
- Envoi d'e-mails à l'acheteur et au vendeur.
- Générer l'avatar d'un utilisateur via laravolt/avatar.



