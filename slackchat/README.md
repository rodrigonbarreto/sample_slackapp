A simple chat in Rails for fun.
# rais 5.0.1
#gems
devise (4.3.0) - https://github.com/plataformatec/devise
cancancan (~> 1.10) - https://github.com/CanCanCommunity/cancancan
materialize-sass (0.98.2) - https://github.com/mkhairi/materialize-sass
material_icons (2.2.1) - https://github.com/Angelmmiguel/material_icons
devise_materialize (~> 1.0.0) - https://github.com/techgurupezza/devise_materialize
factory_girl_rails (4.8.0) - https://github.com/thoughtbot/factory_girl_rails
ffaker (2.5.0) - https://github.com/ffaker/ffaker
rspec-rails (3.6.0) - https://github.com/rspec/rspec-rails
jbuilder (~> 2.5) - https://github.com/rails/jbuilder

#Documentation
Mockflow: https://wireframepro.mockflow.com
Swagger Hub: https://swaggerhub.com

# OthersMaterialize:
http://materializecss.com/

# To run
* docker-compose build
    * to run docker with start file configuration you need to run
 * docker-compose run --rm website bundle exec rails c -> for console.(If you want to test in console)
* docker-compose run --rm website bundle install -> for install bundle
* docker-compose run --rm website bundle exec rake db:create -> create database
* docker-compose run --rm website bundle exec rake db:migrate -> run migrate
