- installed composer.exe (its a dependency manager very similar to npm)
- run 'composer create-project laravel/laravel project-name' - (created a laravel project using composer)
- run 'php artisan serve' after cd to project dir (gives us a local server http://127.0.0.1:8000/ by default)
- un-comment the database section from the .env file change DB_DATABASE to name of the project

- run 'composer require laravel/ui'installs the Laravel UI package, which is an optional frontend scaffolding package for Laravel apps.
- run 'php artisan ui react --auth' to scaffold using React UI and add login/register forms prebuild (auth scaffold)
- run 'npm install' and 'npm run dev' to compile the fresh scaffolding

