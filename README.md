## Database

Using **Postgis**, so we can use geometric data fully.

## Static Files

Using **Nginx** to serve static files

## App

Using **Daphne** to serve Django App


## Usage

`docker compose up -d`

### check container id and enter the container

```
docker container list
docker exec -it <container-id> /bin/sh
```

### create superuser

```
python manage.py migrate
python manage.py createsuperuser
```

### migrate

```
python manage.py migrate
```
