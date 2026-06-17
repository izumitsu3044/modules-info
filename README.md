py -m venv venv
venv\Scripts\activate
pip install django

django-admin startproject shop
python manage.py startapp orders

dobavit v settings orders

napisat models

 python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser

python manage.py runserver
