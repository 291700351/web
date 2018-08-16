FROM nginx
#设置时区
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

COPY ./default.conf /etc/nginx/conf.d
EXPOSE 80
VOLUME [ "/var/log/nginx" ]
