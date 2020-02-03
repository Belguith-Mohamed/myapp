## Project description

The project description goes here

## Install instructions

- run git clone https://github.com/Belguith-Mohamed/myapp.git in a folder in your local host to clone the repository from git servers to your machine.

- run composer install to install composer dependencies

- run npm install to install npm dependencies

- run cp .env.example .env to create .env file for your project

- genereate an encryption key using php artisan key:generate

- create an empty database for your project and fill it's credentials in the .env file

- migrate the database : php artisan migrate

- php artisan passport:install

- php artisan storage:link 

-php artisan serve

## Response to questions

I chosen Laravel framework to work with due to my little experience to work with it in project school recently and due to its performance and support (documentation, communities ...)

in the file (https://github.com/Belguith-Mohamed/myapp/blob/master/app/Http/Controllers/ApiController.php)
- for Air Moon long time response and Air Jazz downtime issues I think loading last time stored results is a good option with setting 3 seconds timeout for Air moon (I thnik more than 3 secs will decrease API performance)
and I have chosen a 50 API call limits (we can change it as we want)

in the file (https://github.com/Belguith-Mohamed/myapp/blob/master/app/Http/Controllers/UserController.php)
-Security part : Authentification and authorization are done with tokens sending (test with Postman with bearer token )




man

