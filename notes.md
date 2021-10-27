# DevOnTheRun Notes

> notes taken during the course

<!-- https://gitignore.io -->

```sh

go mod init goclient

docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin quay.io/keycloak/keycloak:13.0.0

go run main.go
```

Login / Auth
http://localhost:8081/

https://jwt.io/

cd theme
-> docker-compose up

```sh
-> docker-compose exec app bash
bash-4.4$ cd /opt/jboss/keycloak/themes/
bash-4.4$ cp -R keycloak/* mytheme/

rm -rf mytheme/*
bash-4.4$ cp -R base/* mytheme/

```
