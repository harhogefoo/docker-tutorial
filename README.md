# docker tutorial
```
●Dockerイメージに -t でタグを指定する
$ docker build -t friendlyhello .

●構築したイメージの一覧を表示
$ docker images

●バックグラウンドで動作する
$ docker run -d -p 4000:80 friendlyhello
↑実行時に表示されるIDは長いコンテナID

●短縮コンテナIDを確認
$ docker container ls

●プロセスを停止
$ docker stop [CONTAINER ID]

●docker cloudにログイン
$ docker login

●ローカルとリモートのタグを関連付ける
$ docker tag <image_tag> harhogefoo/get-started:part1

●リモートにイメージをアップロードする
$ docker push harhogefoo/get-started:part1

●リモートのイメージを実行する
docker run harhogefoo/get-started:part1


docker-compose exec app bash
```
