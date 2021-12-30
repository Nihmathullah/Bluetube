# Bluetube
A social Media Created on Laravel Platform

steps 

*use git bash to do develop this project

Clone project $ git clone https://github.com/Nihmathullah/Bluetube.git

Go to the folder $ cd Bluetube

Install composer $ composer install

Install npm package $ npm install

Copy and edit .env file from .env.example $ cp .env.example .env

Generate project key $ php artisan key:generate

Create an empty database test for example in phpmyadmin

In the .env file, change database information DB_DATABASE=test

Migrate the database $ php artisan migrate

Create symbolic link for storage $ php artisan storage:link

Run project $ php artisan serve

note if the project doesnt run please use this code at end: $ php -S 127.0.0.1:8000 -t public
