# djangoを使った TODOアプリを作ろう

簡単な Todo を作成するdjangoアプリになります。

## ダウンロード

画面右側の `Code` から `Download ZIP` を押してください。

## makemigrationの実行

- migrationはsqlite3にデータを格納するためのDBとテーブルを準備します。

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

## ユーザーの作成

ユーザーを作成します。管理者権限を保有するユーザーを下記コマンドをターミナル内で実行してください
```bash
$ python manage.py createsuperuser
```

## pythonの起動

以下の runserver をターミナルで実行しインスタント実行いたします。

```bash
$ python manage.py runserver
```

上記まで完了したら http://127.0.0.1:8000/todos にアクセスして TODOアプリが動いているか確認しましょう！
