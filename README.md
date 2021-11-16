command for my testpy

mkdir testpy
cd testpy
py -m venv venv
.\venv\Scripts\activate.bat
pip install django
pip install django_crispy_forms
django-admin startproject testpyproject
cd testpyproject
python manage.py startapp users
python manage.py makemigrations
python manage.py migrate
python manage.py runserver