# drupal-docker-test

docker-compose exec drupal bash -c 'drush site:install minimal --db-url="mysql://drupal:$DRUPAL_DATABASE_PASSWORD@$DRUPAL_DATABASE_HOST/drupal" --site-name="Drupal docker site" -y'

 [success] Installation complete.  User name: admin  User password: fRYYpmGNEp
