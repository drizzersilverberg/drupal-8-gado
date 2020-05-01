# Drupal 8 Gado

A Drupal 8 project to implement any kind of drupal features for learning purpose.

## Quick Start
5. Prepare an empty database in mysql/mariadb server.
1. Setup the project using your prefered local web server solution and point the document root to `/web`.
2. Run `composer install`.
3. Duplicate `web\sites\default\settings.php.gado` into `web\sites\default\settings.php` 
4. Duplicate `web\sites\default\services.yml.gado` into `web\sites\default\services.yml` and configure the settings for your own local development.
5. Open the web in your browser to begin and setup it.
6. Run `./vendor/bin/drush cim` to import the implemented features of the project.