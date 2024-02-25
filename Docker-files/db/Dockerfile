FROM mysql:8.0.33
LABEL "Project"="onlinebookstore"
LABEL "Author"="Akash"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="onlinebookstore"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
