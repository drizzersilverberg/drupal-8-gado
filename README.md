# Drupal 8 Gado

A Drupal 8 project to implement any kind of drupal features for learning purpose.

## Quick Start
1. Prepare an empty database in mysql/mariadb server.
1. Setup the project using your prefered local web server solution and point the document root to `/web`.
1. Run `composer install`.
1. Duplicate `web\sites\default\settings.php.gado` into `web\sites\default\settings.php` 
1. Duplicate `web\sites\default\services.yml.gado` into `web\sites\default\services.yml` and configure the settings for your own local development.
1. Run `/vendor/bin/drush si` to begin site install.
2. Temporary: Run `./vendor/bin/drush config-set "system.site" uuid 8d205929-5213-4226-a3cf-b8ffcb21b55d`
3. Run `./vendor/bin/drush cim` to import the implemented features of the project.