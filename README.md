### Learning Django with Docker


### Create the Django project by running the docker-compose run command as follows.

$ docker-compose run web django-admin startproject mysite .

### Create app

$ docker-compose exec web python manage.py startapp polls

### Tips
* 未使用イメージ一括削除
  $ docker image prune
* 起動中のコンテナ内でコマンド実行
  $ docker-compose exec web python -m django --version
