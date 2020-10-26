# git-pull-deploy-laravel
Script for deploying Laravel


```
cd /absolute/path/to/app
git pull origin master
composer install --no-interaction --no-dev --prefer-dist
php artisan migrate --force
```
