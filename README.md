# yamdb_final
![yamdb_workflow](https://github.com/mamontovdn/yamdb_final/workflows/yamdb_workflow/badge.svg)
### Адрес сайта
http://130.193.36.184
### Документаця
http://130.193.36.184/redoc/ 
### Пример запроса
http://130.193.36.184/api/v1/titles/
## Описание
Сайт является - базой отзывов о фильмах, книгах и музыке.
Пользователи могут оставлять рецензии на произведения, а также комментировать эти рецензии.
Администрация добавляет новые произведения и категории (книга, фильм, музыка и т.д.)
Также присутствует файл docker-compose, позволяющий , быстро развернуть контейнер базы данных (PostgreSQL), контейнер проекта django + gunicorn и контейнер nginx
## Как запустить

Для запуска необходимо из корневой папки проекта ввести в консоль(bash или zsh) команду:
```
docker-compose up --build
```

## Необходимое ПО

Docker: https://www.docker.com/get-started

## Как пользоваться

После запуска проекта, подробную инструкцию можно будет посмотреть по адресу http://0.0.0.0/redoc/

## Автор

* **Дмитрий Мамонтов** - https://github.com/MamontovDN

