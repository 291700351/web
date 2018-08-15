FROM tomcat
#设置时区
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

COPY ./server.xml /usr/local/tomcat/conf/server.xml
COPY ./tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY ./host-manager-context.xml /usr/local/tomcat/webapps/host-manager/META-INF/context.xml
COPY ./manager-context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml
EXPOSE 8080
VOLUME [ "/usr/local/tomcat/logs" ]
