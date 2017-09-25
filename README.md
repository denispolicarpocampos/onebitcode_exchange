## About the project:

This project is a simple app that convert one currency in another currency.

----
## Technologies used:
* Ruby on Rails
* Docker
* API consumption [fixer.io](http://fixer.io/)

----

## Dependencies:
* Ruby on Rails
* Docker
* Postgres

## Getting Started:

After clone the project you need run these commands to up the application:

* docker-compose build
* docker-compose run --rm website bundle exec rake db:create
* docker-compose run --rm website bundle exec rake db:migrate
* docker-compose up
