# README



* docker-compose build
* to run docker with start file configuration you need to run
  - docker-compose run --rm website bundle exec rails c -> for console.(full path)
* for install bundle ->  docker-compose run --rm website bundle install
* docker-compose run --rm website bundle exec rake db:create
* docker-compose run --rm website bundle exec rake db:migrate
