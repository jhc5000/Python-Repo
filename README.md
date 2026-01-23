<!-- to setup a virtual environment in python -->

python -m venv [myworld]
source myworld/bin/activate
python -m pip install Django

to enter and exit venv:
enter: python -m venv [venv name]
exit: deactivate

<!-- setting up new Django project -->

cd into venv folder
django-admin startproject [my_tennis_club]
cd into project folder
run migration cmd: python manage.py migrate
python manage.py runserver
\*remember to have url in allowed hosts
