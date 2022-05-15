# [Django Tutorial](https://docs.djangoproject.com/en/4.0/intro/tutorial01/)

## Development

### Setup

#### Environment

- Create an environment file

```
# .env
DJANGO_SECRET_KEY = some-django-secret-key-123AJDKFbdsfjwiebAFiaj932
DJANGO_DEBUG = True
```

- Create a python virtual environment

```shell
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

#### Pre-commit Hooks
```shell
pre-commit install
```

### Run

```shell
python tutorial_project/manage.py runserver
```
