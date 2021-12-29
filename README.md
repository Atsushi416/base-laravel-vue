# base-laravel-vue
Laravel環境作成用

# 環境構築手順

1. docker立ち上げ

- ルートディレクトリで以下コマンドを入力

```
$ docker-compose up -d
```

2. ブラウザでアクセス

- 下記URLでアクセスできれば成功

```
http://localhost:8080/
```

3. Vueを使用するための準備

    1. Nodeをインストール
    2. ```src/app```で```$ npm install```


# dockerコマンド

- コンテナにアクセス

```
$ docker exec -it {コンテナ名} bash
```

- 停止

```
$ docker-compose stop
```

- 削除

```
$ docker-compose down
```