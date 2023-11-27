# Docker
Aprendizaje de Docker

## Crear imagen de mariadb
docker container run \
-dp 3306:3306 \
--name world-db \
--env MARIADB_USER=example-user \
--env MARIADB_PASSWORD=user-password \
--env MARIADB_ROOT_PASSWORD=root-secret-password \
--env MARIADB_DATABASE=world-db \
mariadb:jammy

Instalamos cliente SQl Server Client(mssql) para comprobar el correcto funcionamiento.