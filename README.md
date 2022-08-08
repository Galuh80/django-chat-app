## Installation

Install virtualenv

```bash
pip install virtualenv
```

Create virtual environment n the project directory.

```bash
virtualenv venv
```

Activate the virtualenv

```bash
source venv/bin/activate
```

Install requirements

```bash
pip install -r requirements.txt
```

Create Database migrations

```bash
python3 manage.py makemigrations
python3 manage.py makemigrations chat
python3 manage.py migrate
```

Try to create a superuser

```bash
python3 manage.py createsuperuser
```

Run server

```bash
python3 manage.py runserver
```
