py -m venv venv

source venv\Scripts\activate

python -m pip install --upgrade pip

pip install django==5.2

django-admin startproject shop

python manage.py startapp orders

dobavit v settings orders

napisat models

 python manage.py makemigrations
 
python manage.py migrate

python manage.py createsuperuser


python manage.py runserver
