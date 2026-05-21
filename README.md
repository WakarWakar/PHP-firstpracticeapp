# PHP-firstpracticeapp
Laravel framework try

Installation steps:

composer install
copy .env.example .env (in powershell)
change contents .env file:
"
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=root
" 

log into mysql: mysql -u root -p (password = root)
CREATE DATABASE your_database_name;
exit;

In php.ini file (path is C:/User/Program Files/php/php.ini) , uncomment -> extension=pdo_mysql

php artisan key:generate

php artisan session:table (might say migration already exists)
php artisan migrate

php artisan serve
