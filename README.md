## Starting

- rails new ruby-book -d postgresql

- rails db:create
- rails g scaffold Greeting name message:text
- rails db:migrate


## Database

- docker run --name postgis --p 5432:5432 -e POSTGRES_PASSWORD=fr@ng0 -d postgis/postgis
# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
