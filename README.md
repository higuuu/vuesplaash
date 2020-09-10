## 操作方法

### 起動

docker-compose up -d

### コンテナ内にログイン

docker-compose exec vuesplash_web bash

### Laravel プロジェクトを作成

composer create-project --prefer-dist laravel/laravel .

### 開発用サーバーを立ち上げる

php artisan serve --host 0.0.0.0 --port 8081

### ホスト側から実行

docker-compose exec vuesplash_web php artisan serve --host 0.0.0.0 --port 8081

### docker 上で環境構築

docker-compose exec vuesplash_web npm install

### コンテナ停止

docker-compose stop