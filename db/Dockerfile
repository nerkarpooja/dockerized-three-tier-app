FROM mysql 
ENV MYSQL_ROOT_PASSWORD=db_password
ENV MYSQL_DATABASE=db_name
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
CMD ["mysqld"]
