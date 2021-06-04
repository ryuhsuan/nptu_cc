# nptu_cc

### Check images:

```sh
$ docker images
```

### Check docker process:

```sh
$ docker ps (show active process only)
$ docker ps -a (show all process)
```

### Check docker logs:

```sh
$ docker logs $CONTAINER_ID
```

### Lunch service:

```sh
$ docker-compose up -d
```

### Rebuild specific service

```sh
$ docker-compose up -d --no-deps --build $SERVICE_NAME 
```

### Restart specific service:

```sh
$ docker-compose restart $SERVICE_NAME
```

### Stop service:

```sh
$ docker-compose down
```

### Build a micro-service:

```sh
$ docker-compose build
```

### Delete necessary images:

```sh
$ docker image prune
```

### Access a running container

```sh
$docker-compose exec $SERVICE_NAME bash
```

### Access a running container

```sh
$ docker exec -it $CONTAINER_ID /bash/bin
```

