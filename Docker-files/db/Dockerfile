FROM mysql:8.0.33

ENV MYSQL_ROOT_PASSWORD='password'
ENV MYSQL_DATABASE='accounts'

COPY db_backup.sql docker-entrypoint-initdb.d/db_backup.sql

EXPOSE 3306