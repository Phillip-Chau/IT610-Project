FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=database
ENV MYSQL_USER=admin
ENV MYSQL_PASSWORD=password

ADD aCode.sql /docker-entrypoint-initdb.d/
