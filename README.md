# 📘 README.md Template — Auto Generated

# composer-npm-node-devlabs
Debugging system devlabs

# 🎯 Gloriabank
# # Gloriabank

Banking frontend app built with:
- Laravel 11
- Jetstream (Inertia + React)
- Vite
- TailwindCSS

## 🚀 Setup

# ```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev

# 🧠 Notes
React pages in resources/js/Pages/

Connects to external Django API

bash
Salin
Edit

# ## 🏭 Gudanglaba
# ```md
# Gudanglaba

Warehouse admin system using:
- Laravel 11
- Jetstream (Livewire + Blade)
- Vue (optional)
- Vite

## 🚀 Setup

# ```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev

## # Dockerfile (Laravel)
FROM php:8.2-fpm
WORKDIR /var/www/html
RUN apt-get update && apt-get install -y \
    zip unzip git curl libzip-dev libpng-dev libonig-dev
RUN docker-php-ext-install pdo pdo_mysql zip
COPY . .
RUN curl -sS https://getcomposer.org/installer | php && mv composer.phar /usr/local/bin/composer
RUN composer install

## ✅ Checklist Final Setup
 Laravel project ready

 Jetstream installed (Inertia & Livewire)

 React & Vue config oke

 NPM/Node handled

 .gitignore clean

 README pro-level

 Docker dev environment

 CI GitHub Workflow
 

## compilled jake and ozx craft dev labs // 
