# docker_compose_django
Quickstart: Compose and Django 

### How to use this ###
Use this for django development
  - running in DEBUG with postsgresql backend (docker container)
  - git clone this repo
  - run docker-compose
  - log by running docker logs -f &lt;web_id&gt;
  - develop webapp in composeexample

Ref: [https://docs.docker.com/compose/django/]

Note: add :z to volumes to 'fix' permission issue

Remember:
  docker-compose run web django-admin.py startproject composeexample .
  sudo chown -R $USER:$USER .

See also
  - [http://www.pedaldrivenprogramming.com/2015/10/sane-django-development-with-docker/]
  - [https://syncano.io/blog/configuring-running-django-celery-docker-containers-pt-1/

