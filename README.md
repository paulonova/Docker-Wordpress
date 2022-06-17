# Docker – AWS – Wordpress. Documentation

## Install Wordpress via composer:

• Check the if you have composer installed.

> composer –version

• Create environment.

> composer require wp-cli/wp-cli-bundle

• Create a wp-cli environment.

> ln -s vendor/wp-cli/wp-cli/bin/wp ./wp

• Test wp-cli version

> ./wp –version

• Download Wordpress

> ./wp core download

• Run server (need to be running to work)

> ./wp server

### 1- Install mysql server

> https://dev.mysql.com/downloads/mysql/

- Update plugins via CLI

  > ./wp plugin update --all

- Search and Replace

  > ./wp search-replace “http://localhost:8080” “http://localhost:9090”

- Clean the cache
  > ./wp cache flush

## Install Wordpress using docker:

Link: https://docs.docker.com/samples/wordpress/

In https://hub.docker.com/

- Search for Wordpress, Mysql and phpmyadmin

Create a yaml file

> touch docker-compose.yml

> docker ps

> docker-compose up -d (Will generate the wordpress)

> docker-compose up
