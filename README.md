開発環境

Dockerビルド

1 git clone git@github.com:seed9103/Laravel-test.git

2 docker-compose up -d --build

Laravel環境構築

1 docker-compose exec php bash

2 composer install

3 .env.example ファイルから.envを作成し、環境変数の変更

4 php artisan key:generate

5 php artisan migrate

使用技術

・PHP 8.3.2

・Laravel　8.83.27

・mysql 8.3.0
