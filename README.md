# go blogr... 
...is a simple blog application rest api in golang using mux as router and gorm as orm.


# Getting started

1.  Start postgres docker instance

```shell
docker run --name blogr_postgres -e POSTGRES_PASSWORD=bl0gr -e POSTGRES_DB=blogr_api -e POSTGRES_USER=blogr -p 5442:5432 -d postgres:alpine
```

2.  Install dependencies
    ```shell
    go mod download
    ```
3.  Start server

    ```shell
    go run cmd/main.go
    ```
4. Access the API from your browser at `:8080`

