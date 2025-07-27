# tree menu django

## Описание

Приложение django для отображения древовидного меню
Используйте тег 'draw_menu' + 'название меню':

```
{% load draw_menu %}
{% draw_menu 'main_menu' %}
```

## установка

Windows:

```shell
git clone https://github.com/Forge-web/tree-menu-django
python -m venv venv
venv/Scripts/activate
pip install -r 'requirements.txt'
cd tree_menu
python manage.py migrate
```

## запуск

```shell
python manage.py createsuperuser
python manage.py runserver
```

## Примечание

Работа, которая послужила примером:

```url
https://github.com/elityaev/tree-menu-django
```
