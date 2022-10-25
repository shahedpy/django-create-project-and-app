# django-create-project-and-app
## create project
```
django-admin startproject projectname
```
## create virtual environment
```
python -m venv venv
```
## activate virtual environment
### linux
```
source venv/bin/activate
```
### windows
```
venv/Scripts/activate
```
## install django in venv
```
python -m pip install django
```
## Requirements.txt
```
pip3 freeze > requirements.txt
```
## runserver
```
python manage.py runserver
```
## Create App
```
python manage.py startapp appname
```
* Write app name in INSTALLED_APPS in "settings.py" file
* Create Template
* Write View
* Create URL

## Run Shell
```
python manage.py shell
```
## Import model in shell
```
from APPNAME.models import CLASSNAME
```
