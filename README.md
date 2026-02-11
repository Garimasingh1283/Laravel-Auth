# Laravel Authentication API (Sanctum)

This project is a **Laravel REST API Authentication Module** using **Laravel Sanctum** for token-based authentication.

It provides basic authentication features such as **User Registration, Login, Logout, and Fetching Authenticated User Details**.

---

## 🚀 Features

- User Registration with validation
- User Login with token generation
- User Logout
- Get Authenticated User details
- Token-based authentication using **Laravel Sanctum**
- JSON-based API responses

---

## 🛠 Tech Stack

- Laravel
- Laravel Sanctum
- PHP
- REST API
- SQLite

---

## 📌 API Endpoints

### ✅ 1. User Registration
**POST** `/api/register`


### ✅ 2. User Registration
**POST** `/api/login`

### ✅ 3. User Registration
**GET** `/api/user`

### ✅ 4. User Registration
**POST** `/api/logout`


## 🚀 Install dependencies
composer install

## Changes in .env file for DB configuration 
DB_CONNECTION=sqlite
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_auth
DB_USERNAME=root
DB_PASSWORD=
<!-- all needs to be commented out -->

## Run migrations 
php artisan migrate

## Install laravel sanctum 
composer require laravel/sanctum
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
php artisan migrate

## Start server 
php artisan serve
