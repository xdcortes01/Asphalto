# ZUUPEE CRM

A demo application to illustrate how Inertia.js works.

![](https://raw.githubusercontent.com/mohsin-shaikh/crm/master/zuupee-crm.png)

## Installation

Clone the repo locally:

```sh
git clone https://github.com/mohsin-shaikh/crm.git crm
cd crm
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm install
```

Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Create an SQLite database. You can also use another database (MySQL, Postgres), simply update your configuration accordingly.

```sh
touch database/database.sqlite
```

Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run the dev server (the output will give the address):

```sh
php artisan serve
```

You're ready to go! Visit ZUUPEE CRM in your browser, and login with:

- **Username:** admin@example.com
- **Password:** Sample@1234

## Running tests

To run the ZUUPEE CRM tests, run:

```
phpunit
```

## License

The ZUUPEE CRM is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
