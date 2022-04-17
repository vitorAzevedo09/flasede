# FastAPI Flasede

### Usage :

#### Start Postgres and FastAPI containers

```docker
docker-compose up -d --build
```

#### Run the tests

```docker
docker-compose exec web pytest .
```

#### Getting inside postgreSQL container

```docker
docker-compose exec db psql --username=flasede --dbname=flasede_db
```
