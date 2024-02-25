FROM mysql:8.0.33
LABEL "Project"="onlinebookstore"
LABEL "Author"="Prarthana"

ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="onlinebookstore"


ADD ./Docker-files/db/db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
