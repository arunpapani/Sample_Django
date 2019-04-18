# Sample_Django

# Intial GitHub setup
1>Create new Repository

2>Open the terminal in your local project location.

3> Run the fallowing commands
>git init

>git add .

>git commmit -m 'message'

4> Copy the URL under Code--> Quick setup 

>git remote add origin https://github.com/arunpapani/Sample_Django.git

5>Puss the code 
>git push -u origin master


# Django_Pro

This is a project created for Django practice purpose:

# Virtual Environment Setup:

>pip install virtualenv

>virtualenv --version

>cd project_folder

>virtualenv 'virtual environment name' (or) virtualenv -p /usr/bin/python3 'virtual environment name'

>source /home/arun/Desktop/Django_Pro/Django_Pro/bin/activate

>python --version

>pip list (it gives the list of the libraries installed int that virtual env)

>pip freeze --local > requirements.txt

>pip install -r requirements.txt (to install the requirements.txt file specific libraries)

# Django project creation:

>pip install django

>python -m django --version

>django-admin startproject <project name>

>python manage.py runserver


# MY SQL SET UP:

https://www.digitalocean.com/community/tutorials/how-to-create-a-django-app-and-connect-it-to-a-database

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'TestDataBase',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST': 'localhost',
        'PORT': '3306',
        'init_command': "SET sql_mode='STRICT_TRANS_TABLES'",
        'OPTIONS': {
            'init_command': 'SET innodb_strict_mode=1',
        },
    }
}



#  HOW TO START THE PROJECT

1> Clone it
git clone https://github.com/arunpapani/Sample_Django.git

2>Activate virtuval Environment
source /home/arun/Documents/sample_django/Sample_Django/Django_Proj_Env/bin/activate
3>Run The server
python migarte runserver
4>Run The urls in browser
http://127.0.0.1:8000/blog/








