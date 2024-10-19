# First Steps

1. Clone this project and create src and mysql folder
2. run docker-compose up -d --build 
3. place your Laravel project to the src folder or create a new project with docker-compose run --rm composer create-project laravel/laravel .
4. in your .env file change DB_CONNECTION to mysql and DB_HOST to mysql

# Composer

docker-compose run --rm composer command eg: create-project laravel/laravel .

# Artisan

docker-compose run --rm artisan command eg: migrate