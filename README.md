# git

### Get git:

```sh
$ git clone $GIT_NETWORKADDRESS
```

### Check directory status:

```sh
$ git status
```

### Add git:

```sh
$ git add $File_NAME
```

### Commit git:

```sh
$ git commit -m 'add a command'
```

### Config git:

```sh
$ git config --global user.name "$GIT_NAME"
$ git config --global user.email "$GIT_EMAIL"
```

### Push git:

```sh
$ git push
```

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

