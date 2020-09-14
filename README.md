docker-compose up --build

docker-compose exec -w /var/www php composer create-project laravel/laravel .
// move files to root

docker-compose exec php npm install
