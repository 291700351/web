FROM mysql
#设置时区
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
COPY ./access.sql /docker-entrypoint-initdb.d 

EXPOSE 3306
VOLUME [ "/var/lib/mysql","/etc/mysql/conf.d" ]