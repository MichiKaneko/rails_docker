# rails_docker
使い方は以下の通りです。
1. docker-compose.ymlを作成
2. docker-fileを作成
3. rootディレクトリで下記コマンドを実行
```console
docker-compose run web rails new . --force --database=mysql
```