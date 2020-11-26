## Configure and run the project on your machine:

-   Install laravel dependencies : composer install
-   Copy .env.example file to .env on the root folder.
    You can type: cp .env.example .env
-   Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration.
-   Run php artisan key:generate
-   Run php artisan migrate
-   Run php artisan serve
