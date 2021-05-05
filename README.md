# Postgres Container

* currently, the actual username/password and db name are set inside `postgres/init.sql`
*  same username/password and db name are also set in `postgres.env`. Pass this file (through `docker-compose`) to your app's container to provide the app with authentication details 

## TODO
* inject env vars from `postgres.env` into `init.sql` via bash script
