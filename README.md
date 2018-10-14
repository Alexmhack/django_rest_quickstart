# django_rest_quickstart
We're going to create a simple API to allow admin users to view and edit the users and groups in the system.

```
# create virtualenv
mkvirtualenv rest

# install packages
pip install django
pip install djangorestframework

# start django project
django-admin startproject tutorial .
python manage.py quickstart
```

Add ```quickstart``` app to the project settings

```
# run migrations
python manage.py migrate

# run server
python manage.py runserver
```
