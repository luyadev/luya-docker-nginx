# luya-docker-nginx
A nginx web process docker image for LUYA

## docker-compose

```yml
  luya_web:
    image: luyadev/luya-docker-nginx
    ports:
      - "8080:80"
    volumes:
      - ./:/app
```
