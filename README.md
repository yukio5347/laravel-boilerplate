# Laravel Boilerplate

This is a boilerplate for Laravel apps with following tools:
- [Laravel 10.10](https://laravel.com/docs/10.x/)
- [DebugBar](https://github.com/barryvdh/laravel-debugbar)
- [TypeScript](https://www.typescriptlang.org/)
- [ESLint](https://eslint.org/) with [Prettier](https://prettier.io/)
- [Husky](https://typicode.github.io/husky/#/) hook with [lint-staged](https://github.com/okonet/lint-staged)

## Initialization

#### Clone the repository and go to the project directory

```bash
git clone git@github.com:yukio5347/laravel-boilerplate.git YOUR_PROJECT_NAME
cd YOUR_PROJECT_NAME && git remote remove origin
```

#### Install packages

```bash
composer install
```

```bash
npm install
```

#### Database Configurations

Create `.env` file.

```bash
cp .env.example .env
```

Define the database constants.

```.env
DB_CONNECTION=
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

Run migration files

```bash
php artisan migrate
```

#### Run local server

```bash
php artisan serve
```
