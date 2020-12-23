# Portfolio

I have tried creating a portfolio using python and Django. In the persistence layer, I have used the default sqlite DB. 

## Commands

##### Add Project
    django-admin startproject portfolio

##### Add App
    django-admin startapp jobs

##### Start App
    python3 manage.py  runserver

##### Make Migration
    python3 manage.py makemigrations

##### Migrate
    python3 manage.py migrate

##### Create Admin User
    $ python3 manage.py createsuperuser
    Username (leave blank to use 'i339952'): satish
    Email address: k*******r@gmail.com
    Password: 
    Password (again): 
    Superuser created successfully.

##### Collect Static
    python3 manage.py collectstatic
    
## Launch URL
    http://127.0.0.1:8000
    
## Admin Url
    http://127.0.0.1:8000/admin    