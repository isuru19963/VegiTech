## Building from the source

If you want to build the project from the source code.

1. Install Composer Dependencies
``composer install``
1. Install NPM Dependencies
``npm install``
1. Create a copy of your .env file
``copy .env.example .env``
1. Generate an app encryption key
``php artisan key:generate``
1. Create an empty database for application
1. Run
``php artisan migrate``
