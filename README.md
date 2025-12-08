# 概要（laravel-start-template）
Laravel環境構築の簡略化が目的。

## 開発環境
|モジュール|バージョン |
|---------|----------|
|nginx    |1.24.0    |
|php      |8.1.26-fpm|
|Laravel  |10.50.0   |
|mysql    |8.0.36    |

## セットアップ手順
```
git clone <このリポジトリ>
cd laravel-start-template/src
cp .env.example .env
composer install
php artisan key:generate
```
※必要に応じて npm install もインストールする

## ディレクトリ構成
src/  
 ├ app/  
 ├ config/  
 ├ routes/  
 ├ public/  
 ├ ...  

## Git 管理しないもの（.gitignore）
vendor/  
node_modules/  
storage/logs  
storage/framework/cache  
.env  

