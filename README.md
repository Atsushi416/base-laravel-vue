# base-laravel-vue
Laravel環境作成用

# 環境構築手順

1. docker立ち上げ

- ルートディレクトリで以下コマンドを入力

```
$ docker-compose up -d
```

2. ブラウザでアクセス
```
http://localhost:8080/
```


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