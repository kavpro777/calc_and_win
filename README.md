# Дипломный проект Foodgram - продуктовый помощник
**Стек технологий:**
- Python 3.9
- Django 3.2.16
- Docker
- PostgreSQL


Адрес сайта:
```
https://foodgramtest.viewdns.net/
```
Описание:

Сервис Foodgram - продуктовый помощник позволяет пользователям создавать рецепты, подписываться на других пользователей а также формировать список покупок необходимых ингредиентов.


Админка:
```
https://foodgramtest.viewdns.net/admin/login/
Username: admin
Password: 1234
Username: alex@ya.ru
Password: Admin12345
```
Пользователь:
```
Username: alex@ya.ru
Password: Admin12345
```


[**Как запустить проект:**](https://github.com/kavpro777/foodgram-project-react/blob/master/README.md)

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/kavpro777/foodgram-project-react.git
```

```
cd foodgram

```

Cоздайте контейнеры и запустите их :

```
docker-compose up -d --build 

```
Выполните миграции:

```
docker-compose exec backend python3 manage.py migrate
```
Соберите статику:

```
docker-compose exec web python manage.py collectstatic --no-input 
```
Создание суперпользователя:

```
docker-compose exec web python manage.py createsuperuser 
```








