django-mini-project

to start vm/workspace:
python -m venv [myworld] 
source myworld/bin/activate 

to install django:
python -m pip install Django

to enter and exit venv: enter: python -m venv [venv name] 
exit: deactivate

to create Django project:
refer to this url for help spinnning up new django project:
https://medium.com/@mathur.danduprolu/a-beginners-guide-to-building-rest-apis-with-python-and-django-rest-framework-ac9153d9ab7a

django-admin startproject [projectName]
cd [projectName]

//to create database tables:
python manage.py makemigrations
python manage.py migrate