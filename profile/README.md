# Lagoon Example Collection

This is a repository of example Lagoon projects - designed for use with [Lagoon](https://lagoon.sh) and it's local development environments.

A subset of these is collected and tested at https://github.com/uselagoon/lagoon-examples

## Templates

- [Drupal9-base](https://github.com/lagoon-examples/drupal9-base) - Drupal 9, PHP 8, NGINX, MariaDB
  - [Drupal9-solr](https://github.com/lagoon-examples/drupal9-solr) - As Drupal9-base, with Solr as a search backend
  - [Drupal9-elastic](https://github.com/lagoon-examples/drupal9-elastic) - As Drupal9-base, with Elasticsearch as a search backend
  - [Drupal9-varnish](https://github.com/lagoon-examples/drupal9-varnish) - As Drupal9-base, with Varnish as an HTTP cache
  - Drupal9-redis - As Drupal9-base, with Redis as a cache backend
- [Drupal9-postgres](https://github.com/lagoon-examples/drupal9-postgres) - Drupal 9, PHP 8, NGINX PostgreSQL
- [wordpress-base](https://github.com/lagoon-examples/wordpress-base) - Wordpress 6, PHP8, NGINX, MariaDB

## Other Examples
- [Ruby-on-rails](https://github.com/lagoon-examples/ruby-on-rails) - RoR 7, Puma 5, NGINX, MariaDB

## Demos

- Node-example
- Silverstripe

## Maintenance of these examples

These repositories are connected to RenovateBot, which will automatically trigger updates when dependencies are available.  We use Github Actions to perform build and test routines. The tests themselves are generated by Leia, from README files in the repositories themselves.
