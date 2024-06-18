# SETUP SYMFONY DOCKER

Clean Symfony App for studies and to begin php projects.

You need only Docker installed to run this app.

## Technologies

- PHP 8.3
- PostgreSQL
- nginx
- Symfony Framework
- PHPUnit

## Getting Started

First clone the repo

`git clone ...`

Go to the path 
`cd setup-symfony-docker`

Run the docker

`docker-compose up -d`

Done, it's all!

Access the link http://localhost:8080

## PHPUnit

To execute phpunit run

`docker exec setup-symfony-php php bin/phpunit`