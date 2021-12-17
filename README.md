# livewire-crud
A Boilerplate Laravel/Livewire Crud Application 
=======

Git clone the project 

````shell
git clone https://github.com/terrymccann/livewire-crud.git
````

Inside the folder you've checked out you run these commands
````shell
composer install
cp .env.example .env
````
Open a new terminal tab

````shell 
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
````
App now available at http://127.0.0.1:8000
