NUOVA INSTALLAZIONE

docker-compose up -d
docker-compose exec php bash
composer install
chmod 777 web/sites/default/files
chmod 777 web/sites/default/settings.php 

visita http://drupal.docker.localhost:8000/

Configurazione database:

Nome database: drupal
Nome utente: drupal
Password: drupal
Host: mysql