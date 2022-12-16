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

# deploy the dev app: ./bin/dev 
# create controller: rails g controller "MAIN" + define the paths example : home, about.
# Take out default landing page: routes.rb change default to this: root 'main#home'