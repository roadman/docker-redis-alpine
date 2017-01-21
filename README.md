# docker-redis-alpine

## build

```
$ docker build -t roadman/redis:v1 .
```

## run

```
$ docker run -d --name redis -v /data:/data roadman/redis:v1
```
