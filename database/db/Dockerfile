FROM mysql
WORKDIR /tmp
COPY data/testdb.sql /docker-entrypoint-initdb.d
ENV MYSQL_ROOT_PASSWORD root