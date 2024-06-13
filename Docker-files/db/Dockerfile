FROM mysql:8.0.33
LABEL "Project"="vprofile"
LABEL "Author"="Nishtha"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="account"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql