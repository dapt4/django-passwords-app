# django-passwords-app

first create your virtualenv

`$ python3 -m venv venv`

activate venv

`$ source venv/bin/activate`

then install requeriments

`$ pip install -r requirements.txt`


create a .env file in the root folder

`$ touch .env`

and add your postgresql credentials and the app SECRET_KEY to .env file

>ENV_SECRET_KEY="{add a secret key like bhajfbkjhawbdkjhabdjh}"

run the command:
`python manage.py migrate`

finally the project run with: 

`$ python manage.py runserver`

open your browser in: 

`http://localhost:8000/`
