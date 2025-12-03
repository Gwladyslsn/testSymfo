-- SYMFONY --

Premier essai d'integration symfony via Docker

Ce projet utilise :
- PHP 8.2 (Apache)
- Composer
- MySQL 8
- Docker & Docker Compose

1. Lancer environnement Docker 
    - docker compose up -d --build

2. Entrer dans le conteneur PHP
    - docker exec -it php_apache_symfony bash

3. Installer Symfony (si ce n’est pas déjà fait)
    - composer create-project symfony/skeleton:"7.0.*" .
    - composer require webapp

4. Configuration de la base de données
    - Faire le fichier .env à l'aide du fichier .env.example