## Tutorial 
`https://www.youtube.com/playlist?list=PLQDioScEMUhl_vDV7BcYTUdTU4Jz8g58X`

## How to install laravel 10
composer create-project laravel/laravel:^10.0 example-app

## Requirements 
PHP - 8.2.*
Cpmposer-2.7.7

## WebSocket Command 
(Tutorial Version) 1.13.2
1. composer require beyondcode/laravel-websockets
/ composer require beyondcode/laravel-websockets -W


2. php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="migrations"

3. php artisan migrate

4. php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="config"

5. composer require pusher/pusher-php-server "~3.0"
