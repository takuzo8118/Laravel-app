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

