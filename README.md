# Laravel Boilerplate
[![GitHub license](https://img.shields.io/github/license/viralsolani/laravel-adminpanel.svg?style=plastic)]()

## [Demo App](https://demo1.danuwijaya.com/)

## Additional Features
* Built-in Laravel Boilerplate Module Generator,
* Dynamic Menu/Sidebar Builder
* Pages Module
* API Boilerplate
* Mailables
* Responses
* Vue Components
* Laravel Mix
* Object based javascript Implementation



## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/5.6/installation#installation)


Clone the repository

    git clone https://github.com/danudenny/laravel_boilerplate.git

Switch to the repo folder

    cd laravel_boilerplate

If you have linux system, you can execute the command below only in your project root

    1) sudo chmod -R 777 install.sh
    2) ./install.sh

If you have windows system, you can run Artisan Command for database setup, connection and configuration.

    php artisan install:app

Generate a new application key

    php artisan key:generate

Install Passport

    php artisan passport:install

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate

Run the database seeders

    php artisan db:seed

Install the javascript dependencies using npm

    npm install

Compile the dependencies

    npm run development

For generating the files of unisharp file manager

    php artisan vendor:publish --tag=lfm_public

For linking storage folder in public

    php artisan storage:link

Start the local development server

    php artisan serve


You can now access the server at http://localhost:8000

---

## License
[MIT LICENSE](https://github.com/danudenny/laravel_boilerplate/blob/master/LICENSE.txt)
