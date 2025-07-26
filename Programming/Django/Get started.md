```shell
django-admin startproject xxx
```
*Create a project by command*

```shell
python manage.py startapp app
```
*Create an app folder by command*

- Go to the setting.py file
```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app',
```
*Add `'app'` in the last row*

```shell
python manage.py runserver
```
*Runing the server*
	IP -> 127.0.0.1:8000
