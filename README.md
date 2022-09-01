# Project Set up
Create a new Django project by executing the command below.
```bash
$ django-admin startproject djangotesting
```

The above command generates a Django application named djangotesting.
A Django project is usually organized into applications. This makes it easy to manage larger projects. Let’s create a new Django application in our project by executing the command below.

```bash
$ python manage.py startapp testing
```

Add django restframework to the application by executing the command below.
```bash
$ pip install djangorestframework
```

Once djangorestframework is installed in our application, we need to add it to the settings.py file in the INSTALLED_APPS list as shown below.
```python
INSTALLED_APPS = [
 'django.contrib.admin',
 'django.contrib.auth',
 'django.contrib.contenttypes',
 'django.contrib.sessions',
 'django.contrib.messages',
 'django.contrib.staticfiles',
 'testing.apps.TestingConfig',
 'rest_framework'
]   
```

