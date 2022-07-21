# environment-docker-laravel

## Get Start

`docker-compose up -d --build`

### Up volumes

`docker-compose exec php php -vdocker-compose run composer -vdocker-compose run npm -vdocker-compose run mysql -v`

### Create new folder

`mkdir src`

### Open src folder

`cd src`

### Create new project laravel 

`docker-compose run composer create-project laravel/laravel .`

### Check version

`docker-compose exec php php artisan -V`

### Run

`docker-compose exec php php artisan serve`
