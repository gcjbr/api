# Setup

- Copy .env.example to .env
- On api/ run composer install
- On api/ run php artisan key:generate
- On api/ run php artisan migrate --seed
- On api/ run php artisan serve to start the api server