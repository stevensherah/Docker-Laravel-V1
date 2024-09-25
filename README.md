# Docker-Laravel-V1
An example project for installing docker add laravel with it is Laravel v11.24.1 (PHP v8.3.11).

# Set-Up

docker-compose run --rm composer create-project laravel/laravel src

docker-compose build --no-cache

docker-compose run --rm composer update

docker-compose run --rm artisan migrate

docker-compose run --rm artisan key:generate

docker-compose up -d --build site

docker-compose up -d --build site
