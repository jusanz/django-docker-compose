## Docker Compose

`docker compose up -d`

## Docker

### Build Image

`docker build -f./Dockerfile . -t remix/huwd`

### Run Image

`docker run -p 3000:3000 -d remix/huwd`

### View Running Containers

`docker ps`

### View Log

`docker logs <container-id>`

### Go inside the container

`docker exec -it <container-id> /bin/sh`

## Install

```
docker container list
docker exec -it <container-id. /bin/sh
```

```
python manage.py migrate
python manage.py createsuperuser
```
