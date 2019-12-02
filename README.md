# docker-laravel-template

Build Laravel's development environment using docker.
PHP7.3/MySQL8.0/nginx/node/redis/mailhog

## Build

- docker-compose build

## up

- docker-compose up -d

## access

- localhost:10080

## login app container

- docker-compose exec app ash

## create project

- composer create-project --prefer-dist laravel/laravel .

### Laravel のディレクトリについて

- モデル
  - app/Models
- サービス
  - app/Services
- リポジトリ
  - app/Repositories
