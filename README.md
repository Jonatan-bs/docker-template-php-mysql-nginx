## Start container
docker-compose up

## Create Laravel project
docker-compose exec -w /var/www php composer create-project laravel/laravel ./html\
**OBS Move files to root directory after install**

## Init yarn
docker-compose exec php npm init
