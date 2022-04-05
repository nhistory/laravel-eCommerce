## About project

This is a simple eCommerce website project by using laravel, bootstrap, jQuery.

-   PHP : 8.1.4
-   composer : 2.3.2
-   mySQL : 8.0.28
-   phpMyAdmin : 5.1.3

## How to setup

-   Build up laravel project : `composer create-project laravel/laravel laravel-eCommerce`
-   server activate : `php artisan serve`
-   database migration : `php artisan make:migration create_[table name]_table`
-   DB setup : .env (DB_DATABASE=`data name` / DB_USERNAME=`user name` / DB_PASSWORD=`password`)
-   create seeder : `php artisan make:seeder [seeder name]`
-   database seeding : `php artisan db:seed --class [seeder name]`
