# Drupal served by nginx/php-fpm with mysql
The idea here is to provide support for drupal via docker-compose.
The end goal will be to serve a local drupal site without requiring php/composer on the local machine.
The next steps are to create a bind mount for modules, `sites/default/files`, etc.
I'd like to create my own nginx/fpm/drupal image at some point as well.
After that will be the k8s deployment.