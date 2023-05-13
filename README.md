# docker-fastapi

## Build container image
```sh
finch build -t docker-fastapi .
```

## Run container
```sh
finch run -d --name docker-fastapi -p 80:80 docker-fastapi
```

## Hello, world
```sh
curl localhost
```

## Access to FastAPI
```sh
curl "localhost/items/5?q=somequery"
```
## Stop container
```sh
finch stop docker-fastapi
```

## Remove container
```sh
finch rm docker-fastapi
```