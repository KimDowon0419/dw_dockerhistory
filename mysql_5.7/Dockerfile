FROM mysql:5.7

COPY ./utf8.cnf /etc/mysql/conf.d/
COPY ./Dump1.sql /docker-entrypoint-initdb.d/
