## Swagger docs setup in django rest framework

## Building
Clone the repo
```sh
git clone https://github.com/andwati/drf-swagger.git
```
```sh
cd drf-swagger
```
The project uses [pipenv](https://github.com/pypa/pipenv) for dependency management

```sh
pipenv install && pipenv shell
```

Initialize the pre-commit hooks
```sh
pre-commit install
```

```sh
pre-commit run --all-files
```
Do the migrations
```sh
python manage.py makemigrations
```
```sh
python manage.py migrate
```
Create a super user to authenticate the requests
```sh
python manage.py createsuperuser
```

Run the project
```sh
python manage.py runserver
```
Navigate to `http://localhost:8000/docs/`
## Screenshot
![Swagger Screenshot](/screenshots/ss1.png)
