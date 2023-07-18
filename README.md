# アプリの起動方法

- Docker Composeでコンテナを作成

```
$ docker compose up -d
```

## API側

- 新しいターミナルを開く

- 以下のコマンドを実行する

```
$ docker compose exec api bash
```

- 以下のコマンドを実行し、API側を起動する

```
$ cd workspace
$ ./gradlew bootRun
```

## Web側

- 新しいターミナルを開く

- 以下のコマンドを実行する

```
$ docker compose exec web bash
```

- 以下のコマンドを実行し、ライブラリをインストールする

```
$ cd workspace
$ npm install
```

- 以下のコマンドを実行し、Web側を起動する。

```
$ npm run start
```