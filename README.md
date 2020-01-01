Laravel 6.9.0 Auth's Configuration

### 1. Laravel Installation

> `laravel new laravel_auth` <br>
> `cd laravel_auth`

### 2. Database

Create a database on your local server.

> `Database name : laravel_auth`

Open ".env" file and edit it

> `DB_DATABASE=laravel_auth ` <br>
> `DB_USERNAME=root`<br>
> `DB_PASSWORD=` 

### 3. Do migration

Back to the terminal, write this command

> `php artisan migrate`

If it works sucessfully then you can find on the database that there will be several tables are added 

### 4. Add UI

> `composer require laravel/ui`

> `php artisan ui vue --auth`

Check the reuslt in browser, but first, type this command

> `php artisan serve`

Type the address (http://127.0.0.1:8000) on address bar on your browser

You may will see that the css doesn't work, so you need to type hese commands

> `npm install`

> `npm run dev`

> `php artisan serve`

Now, open browser again and check it. You can register, logout and login using the facilities.
