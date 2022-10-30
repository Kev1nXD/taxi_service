# Taxi Service

Django project for managing drivers, cars, and manufacturers.

## Check it out!
Project was deployed on [Heroku](Link) (tap to see it).

## Installation

Python3 is required

```shell
git clone https://github.com/Kev1nXD/taxi_service.git
cd taxi_service
python3 -m venvvenv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
pip install -r requirements.txt
python manage.py runserver
```

After all commands you have run, you will see a local link on a website in your terminal.

### Initial Configuration

to get access to pages with limited access you will need to create superuser
and log in with credentials you inserted on log in page:
```shell
python manage.py createsuperuser
```

## Features

* Authentication functionality for Driver/User
* Managing drivers, cars, manufacturers with website interface
* Powerful admin panel for advanced managing

## Demo
![Website Homepage](demo.png)
