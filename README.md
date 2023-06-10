## Membuat project
composer create-project laravel/laravel crud

## Membuat Controller
php artisan make:controller PegawaiController --resource

## Membuat Model
php artisan make:model mahasiswa -m

## Membuat Seeder
sebuah fitur untuk mengisi data ke database dengan data sembarang atau data testing

- php artisan make:seeder PegawaiSeeder
- php artisan db:seed --class=PegawaiSeeder

## Setup dari github
- buka direktori project di terminal anda.
- ketikan command : cp .env.example .env (copy paste file .env.example)
- buat database

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear
- php artisan key:generate (generate app key)
- php artisan migrate (migrasi database)
- php artisan db:seed 

