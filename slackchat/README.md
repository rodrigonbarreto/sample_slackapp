A simple slack in Rails for fun.

# rais 5.0.1

#gems
gem 'devise'
gem 'cancancan'
gem 'materialize-sass'
gem 'material_icons'
gem 'redis'
=======
#To run
* docker-compose build
    * to run docker with start file configuration you need to run
 * docker-compose run --rm website bundle exec rails c -> for console.(If you want to test in console)
* docker-compose run --rm website bundle install -> for install bundle
* docker-compose run --rm website bundle exec rake db:create -> create database
* docker-compose run --rm website bundle exec rake db:migrate -> run migrate
