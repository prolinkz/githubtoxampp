# githubtoxampp

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## How To Run Downloaded Laravel Projects From GITHUB on localhost XAMPP

Add command execution process to clone Laravel project from GitHub to Xampp directory and run on localhost.


### How to Run the composer Command Code

- [Clone] git clone gitURL 
- [Enter project directory] cd laravel starter
- cp .env.example <code>.env</code>
- open .env and update DB_DATABASE
- run: composer install
- run: php artisan key:generate
- run: php artisan miigrate:fresh --seed
- run: <code> php artisan serve </code>
