# CINEMA API

REST API for cinema

Technologies used:
- Django REST Framework
- PostgreSQL
- Docker
## Installing using GitHub:

```shell
  git clone https://github.com/Danil228/cinema_api.git
  cd cinema_api
  python -m venv venv
Linux/macOS:
  source venv/bin/activate
  pip install -r requirements.txt
  export DB_HOST=<your db hostname>
  export DB_NAME=<your db name>
  export DB_USER=<your db user>
  export DB_PASSWORD=<your db password>
  export DB_SECRET_KEY=<your secret key>
Windows: 
  venv\Scripts\activate
  pip install -r requirements.txt
  set DB_HOST=<your db hostname>
  set DB_NAME=<your db name>
  set DB_USER=<your db user>
  set DB_PASSWORD=<your db password>
  set DB_SECRET_KEY=<your secret key>
  python manage.py migrate
  python manage.py runserver
```

## Run with docker:
```shell
  docker-compose up --build
```
  

## Features:

- Authenticate with JWT
- Admin panel (/admin/)
- SWAGER documentation (/api/doc/swagger/) 
- Managing orders and tickets
- Creating cinema halls
- Creating movies with genres, actors
- Adding movie sessions
- Filtering movies and movie sessions

## Access:
- creating user (/api/user/register/) 
- get a JWT token to use (/api/user/token/)
