<h3>Create a PostgreSQL instance with Docker:</h3>

```console
docker run --name ead-notification -e POSTGRES_PASSWORD=notification -e POSTGRES_USER=notification -e POSTGRES_DB=ead-notification -p 5434:5432 -d postgres
