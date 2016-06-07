# django-rest-framework-tutorial

This is the DRF [tutorial](http://www.django-rest-framework.org/tutorial/1-serialization/)

```shell
pip install django djangorestframework httpie
python manage.py migrate
python manage.py createsuperuser
http -a username:password GET http://localhost:8004/users/
```