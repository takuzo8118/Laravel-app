# laravel-app
こちらのディレクトリ内の解説を書いておきます。
Laravel Framework v9.40.1
phpのversionはエラーが出たためphp-8.1-fpmに変更して実行
php 8.1.12
nginx v1.2-alpine
mysql/mysql-server 8.0.31→M1Macはエラーが出るため変更
phpmyadmin → v***

<!-- 実行したlaravelコマンドについて -->
--prefer-dist zipでダウンロードするため高速 

laravel立ち上げた時にNotFound
src内にlaravelディレクトリを作成しまっていたのでpassが合わずに表示できていなかった。
そのため、srcの中からlaravelディレクトリを取り出し
srcを削除→laravelの名前を「src」に変更したら動きました。
ここに書くのはそういうことではない気がしますが・・・
## 参考
### php: 8.1-fpm-buster
ピーエッチピー、プログラミング言語
公式: https://www.php.net
PHPとは: https://www.php.net/manual/ja/intro-whatis.php
Dockerイメージ: https://hub.docker.com/_/php
### composer: 2.2
コンポーザー、PHPのパッケージ管理ツール
公式: https://getcomposer.org
Composerとは: https://getcomposer.org/doc/00-intro.md
Dockerイメージ: https://hub.docker.com/_/composer
### nginx: 1.20-alpine
エンジンエックス、ウェブサーバー
公式: https://www.nginx.com
nginxとは: https://nginx.org/en
Dockerイメージ: https://hub.docker.com/_/nginx
### mysql/mysql-server: 8.0
マイエスキューエル、データベースサーバー
公式: https://www.mysql.com/jp
MySQLとは: https://ja.wikipedia.org/wiki/MySQL
Dockerイメージ: https://hub.docker.com/r/mysql/mysql-server
### Laravel: 9.x
ララベル、PHPのフレームワーク
公式: https://laravel.com
Laravelとは: https://readouble.com/laravel/9.x/ja/installation.html#why-laravel
Laravel本体: https://github.com/laravel/framework

