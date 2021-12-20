# docker-compose-example

## commands

`docker-compose up`

`docker-compose down`

`docker-compose stop`

`docker-compose start`

## test

```bash
bash-4.2$ curl http://172.27.0.3:6000/
Hello World! I have been seen 1 times.
bash-4.2$ curl http://172.27.0.3:6000/
Hello World! I have been seen 2 times.
bash-4.2$ curl http://172.27.0.3:6000/
Hello World! I have been seen 3 times.
```

## reference 

[get started with docker compose](https://docs.docker.com/compose/gettingstarted/)