FROM tomcat:9-jdk11
EXPOSE 8080
RUN mkdir -p /opt/data/db /opt/data/file /opt/data/filekanri /opt/data/webmail
COPY gsession.war $CATALINA_HOME/webapps/
