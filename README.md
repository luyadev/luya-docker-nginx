<p align="center">
  <img src="https://raw.githubusercontent.com/luyadev/luya/master/docs/logo/luya-logo-0.2x.png" alt="LUYA Logo"/>
</p>

# LUYA NGINX Docker

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
