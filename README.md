![datatable](https://user-images.githubusercontent.com/128790623/236443974-73aef7b2-e2bf-4213-aecc-f0a83a3d6c1e.png)
![crete](https://user-images.githubusercontent.com/128790623/236443979-163e972a-e829-4fb2-b535-de7cb45293cb.png)

How to run the code

git clone https://github.com/sabarishkarmegamk/laravel_crud.git

cd  laravel_crud

cp .env.example .env

open .env and update DB_DATABASE (database details)

run : composer install

run : php artisan key:generate

run : php artisan migrate:fresh --seed

run : php artisan serve

http://127.0.0.1:8000/companies
