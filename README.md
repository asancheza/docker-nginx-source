# Docker nginx

## Build

```
docker build -t nginx .
```

## Run

```
docker run -it -p 80:80 nginx
```

## Logs

```
docker exec -it nginx tail -f /var/log/nginx/access.log
```
