# django-react-boilerplate

A simple straight forward [django](https://www.djangoproject.com/) boilerplate/template with 
- [django-rest-framework](https://www.django-rest-framework.org/)
- [react](https://reactjs.org/)
- [redux](https://redux.js.org/)

### Instructions

Create Virtual Env

```text
python3 venv env
```

Activatge Env

```text
source env/bin/activate
```

To Deactivate

```text
deactivate
```

**NOTE if using linux** make sure to install postgress and some dependencies to work with python

```text
sudo apt-get install postgresql postgresql-contrib
```

```text
sudo apt-get install libpq-dev python3.7-dev
```

Install Requirements

```text
pip3 install -r requirements.txt
```

Update DB info in `backend/backend/settings.py` file


### Delete Migrations In Case

```text
find . -path "*/migrations/*.py" -not -name "__init__.py" -delete
```

```text
find . -path "*/migrations/*.pyc"  -delete
```
