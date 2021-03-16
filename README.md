# Registration
 Регистрация и авторизация Jetstream в laravel 8

composer require laravel/jetstream
php artisan jetstream:install inertia
npm install
npm run dev

Настройка подключения к базе данных в .env

php artisan migrate
php artisan storage:link

Composer должен быть версии >= 2.0!

Установить русификацию приложения
https://github.com/Laravel-Lang/lang

Скопировать из vendor/laravel-lang/lang в resources/lang,
из src/ru папку языка и из json/ru файл
