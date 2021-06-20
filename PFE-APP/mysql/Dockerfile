FROM mysql:5.7

#
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=testing
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=12345
VOLUME /var/lib/mysql
#
EXPOSE 3306
#
COPY src/*.sql /docker-entrypoint-initdb.d/