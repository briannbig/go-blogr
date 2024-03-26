# go blogr... 
...is a simple blog application rest api in golang using mux as router and gorm as orm.

## getting started
- git clone this repo on your local machine.
- run `go mod download` to download dependencies
- You will need a database connection(postgresql, mysql, etc).
  - the following is an example of spinning a docker postgres docker instance. `docker run --name blogr_postgres -e POSTGRES_PASSWORD=bl0gr -e POSTGRES_DB=blogr_api -e POSTGRES_USER=blogr -p 5442:5432 -d postgres:alpine`
  - copy or rename the `.env.sample` file to `.env` and update the variables according to your database.
