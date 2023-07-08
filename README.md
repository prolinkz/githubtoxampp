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
- [Enter project directory] <code> cd project-folder </code>
-  <code> cp .env.example </code> &nbsp; <code> .env </code>
- open: .env and update DB_DATABASE
- run: <code> composer install </code>
- run: <code> php artisan key:generate </code>
- run: <code> php artisan migrate:fresh --seed </code>  <a href="https://laravel.com/docs/10.x/migrations" alt="migration commands">migration commands </a>
- run: <code> php artisan serve </code>

Here is the graphical representation of commands running.
![image](https://github.com/prolinkz/githubtoxampp/assets/45316278/8d6b20a0-e8b4-4169-9e15-ec44db776638)





## ReInstall the Composer if it NOT WORK's 

```
composer reinstall
```

<p>  </p>

```
composer update
```

<p>  </p>

```
php artisan cache:clear
```

```
php artisan config:clear
```

<p>  </p>


```
composer dump-autoload
```

<p>  </p>

```
php artisan optimize
```
<p>  </p>

```
php artisan key:generate
```

<p>  </p>

- run: <code> php artisan serve </code>
