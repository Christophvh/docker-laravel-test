## sample laravel project setup with docker

Build:
docker-compose up -d --build

Run commands inside docker containers

docker-compose run --rm composer update
docker-compose run --rm npm run dev
docker-compose run --rm artisan migrate
