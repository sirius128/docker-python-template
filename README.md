# What is this?
Docker Compose を利用して Python 3.12 の実行環境を構築するテンプレートです。

# How to use
1. このリポジトリをクローンします。
2. 必要があれば `Dockerfile` を編集して、コンテナ起動時に実行したいファイル名を指定します。
3. 同様に、必要があれば `requirements.txt` を編集して、インストールしたいパッケージを指定します。
4. `docker compose build` を実行します。
5. `docker compose up -d` を実行します。

または、 `docker compose run --rm python python <実行したいファイル名>` でコンテナを起動し、ファイルを実行することもできます。
