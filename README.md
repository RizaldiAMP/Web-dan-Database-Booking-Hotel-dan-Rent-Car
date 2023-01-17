## Spesifikasi
PHP ^8.1
Database MySQL atau MariaDB
SQlite (untuk automated testing)
## Cara Install
Clone atau download source code
Para terminal, clone repo git clone https://github.com/nipengg/WebHotel
Jika tidak menggunakan Git, silakan Download Zip dan extract pada direktori web server (misal: xampp/htdocs)
Jika menggunakan laragon silakan extract pada direktori laragon/www
cd WebHotel
composer install
npm install
cp .env.example .env
Jika tidak menggunakan Git, bisa copy file .env.example paste menjadi .env
Pada terminal php artisan key:generate
Buat database pada mysql untuk aplikasi ini
Setting database pada file .env
php artisan migrate untuk migrate table
php artisan db:seed untuk eksekusi seeder akun
php artisan serve
Selesai
