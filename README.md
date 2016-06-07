# django-rest-framework-tutorial

This is the DRF [tutorial](http://www.django-rest-framework.org/tutorial/1-serialization/)


	1 - Serialization
	2 - Requests and responses
	3 - Class based views
	4 - Authentication and permissions
	5 - Relationships and hyperlinked APIs
	6 - Viewsets and routers
	
```shell
pip install django djangorestframework httpie
python manage.py migrate
python manage.py createsuperuser
http -a username:password GET http://localhost:8004/users/
```