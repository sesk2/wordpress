# wordpress
wordpress & mysql for wordpress

## start container
```
export MYSQL_PASS='{password}'  # set mysql password for wordpress user
docker-compose up -d
docker-compose ps
```

## access wordpress
URL: http://{IP}

## login container
```
docker exec -it wordpress|mysql /bin/sh
```

## stop container
```
docker-compose stop
```

## down(stop & remove) container
```
docker-compose down
```

## check logs
```
docker logs wordpress|mysql
```
