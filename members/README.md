## Laravelを用いた新規登録 - ログイン - チャット - 編集

### 開始方法
php artisan serve もしくはlocalhost:ファイルパス

### バージョン
Laravel 8.x

### 使用コマンド
composer create-project "laravel/laravel=8.*" members

#### 以下membersディレクトリ

composer require laravel/ui

php artisan ui bootstrap --auth

php -r "copy('https://readouble.com/laravel/8.x/ja/install-ja-lang-files.php', 'install-ja-lang.php');"

php artisan make:model Post -m

php artisan make:controller PostController --resource

php artisan storage:link

### 参考資料
src(https://biz.addisteria.com/laravel_textbook_contents/)