# Starting postgres docker instance example:
`docker run --name blogr_postgres -e POSTGRES_PASSWORD=bl0gr -e POSTGRES_DB=blogr_api -e POSTGRES_USER=blogr -p 5442:5432 -d postgres:alpine`

