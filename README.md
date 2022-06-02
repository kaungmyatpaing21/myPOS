<p align="center">
    <h1 align="center">POS System Using Laravel</h1>
</p>

## Installation

### Clone the repository from github.

    git clone https://github.com/kaungmyatpaing21/myPOS.git [YourDirectoryName]

### Install dependencies

    cd YourDirectoryName
    composer install

### Config file

Rename or copy `.env.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file.

### Database

1. Migrate database table `php artisan migrate`
1. `php artisan db:seed`, this will initialize settings and create and admin user for you [email: admin@gmail.com  - password: admin123]

### Install Node Dependencies(optional)

1. `npm install` to install node dependencies
1. `npm run dev` to build javascript

### Create storage link

`php artisan storage:link`

### Run Server

1. `php artisan serve` 
