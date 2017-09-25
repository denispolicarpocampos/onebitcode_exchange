## About the project:

This project is a simple app that convert one currency in another currency.

![Bootcamp-exchange](https://raw.githubusercontent.com/denispolicarpocampos/onebitcode_exchange/4119126cb5b945c665cda6c3d5e57328082592e7/app.png)
----
## Link on Heroku:
http://exchangemoneyapp.herokuapp.com/

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

----
## Getting Started:

After clone the project you need run these commands to up the application:

* docker-compose build
* docker-compose run --rm website bundle exec rake db:create
* docker-compose run --rm website bundle exec rake db:migrate
* docker-compose up
