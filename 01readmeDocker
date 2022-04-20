Ссылка на офицальный сайт с документаций Docker
https://docs.docker.com/install/linux/docker-ce/ubuntu/

Установка Docker под Windows
https://hub.docker.com/?overlay=onboarding

$ lsb_release -a
Ubuntu 18.04.1 LTS
or
Debian GNU/Linux 10 (buster)

$ sudo apt-get update

$ sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

$ sudo apt-get update

$ sudo apt-get install docker-ce docker-ce-cli containerd.io

$ sudo docker run hello-world


To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/
 
For more examples and ideas, visit:
 https://docs.docker.com/get-started/


$ git clone https://github.com/atutby/shop.git

$ cd shop

# create file: Dockerfile
#create folder: /app

$ sudo docker build .

# create file: docker-compose.yml

# Переходим в режим суперпользователя
$ sudo -s
$ docker-compose build

$ docker-compose run app sh -c "django-admin.py startproject app ."


$ docker-compose up

# Переходим на: 127.0.0.1:8000

$ Ctrl-C

# создаём файл: /.travis.yml
# обновили файлы: Dockerfile docker-compose.yml requirements.txt
# создаём файл: /app/.flake8 рядом с manage.py
# обновляем файл: /app/app/settings.py

# Входим в sudo:
$ sudo -s
$ docker-compose build


# Поднимаем сервер:
$ docker-compose up
# Всё запустилось, правда пришлось закрыть терминал и запустить

# Останавливаем сервер:
$ Ctrl-C
$ git status
$ git add .
$ git commit -m 'First lesson commit#2 add 01readmeDocker .travis .flake8 and update files'


# time 01:04:20


# заходим на сайт https://travis-ci.org и авторизуемся
    Since June 15th, 2021, the building on travis-ci.org is ceased. Please use travis-ci.com from now on.
# заходим на www.travis-ci.com
# активируем репозиторий с github
# https://app.travis-ci.com/getting_started
# Нажимаем кнопку: Sync account


$ git add .
$ git commit -m "First commit for ITVDN COURSE"


$ git push origin # не сработала поэтому делаем следующее
# зашёл на https://www.youtube.com/watch?v=SdILWnuiMOY (Дмитрий Тхоржевский)
# https://www.kobzarev.com/programming/use-token-for-github-actions-with-private-repositories/
#
$ git branch -M admin
$ git remote add origin https://github.com/atutby/shop.git
$ git push -u origin main # не сработало опять и выдало ошибку: необходимости сгенерировать специальный token
# Посмотрим содержимое config
$ cat .git/config
# На сайте www.github.com переходим:
    Settings >
    (внизу) Developer settings >
    (раздел) Personal access tokens >
    (кнопка) Generage new token >
        (на странице указываем)
        Note: shop
        Expiration: 30 days (May 20 2022) 
        Select scopes: (отметил все)
        (кнопка внизу) Generate token >
    (копируем token) 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28
    (теперь будем токен вводить вместо пароля: $ git push)


$ git push -u origin main
# в последующем делаем только $ git push

# если необходимо выполнить отдельные команды то делаем так:
$ docker-compose run app sh -c "python manage.py createsuperuser"
# superuser:ADS8JAsjjS28:superuser@gmail.com

