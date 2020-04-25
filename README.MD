#### Git repository for article https://medium.com/@adigunhammedolalekan/build-and-deploy-a-secure-rest-api-with-go-postgresql-jwt-and-gorm-6fadf3da505b



Build docker image using:

```
dockerize -f main.go -n us.icr.io/grizano/go-contacts -p
```

Run with compose:

```
$ DB_PASSWORD="PASSWORD" docker-compose up
```
