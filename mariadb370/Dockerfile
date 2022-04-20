# Dockerfile
# syntax=docker/dockerfile:1

# Dockerfile
FROM mariadb


ENV MARIADB_ROOT_PASSWORD=root
ENV MARIADB_DATABASE=ead_bd
ENV MARIADB_USER=ead_user
ENV MARIADB_PASSWORD=ead_pass



ADD ./db/dump.sql /docker-entrypoint-initdb.d/dump.sql




