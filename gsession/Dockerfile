FROM tomcat:9-jdk11
EXPOSE 8080
RUN mkdir -p /opt/data/db /opt/data/file /opt/data/filekanri /opt/data/webmail
#ADD https://www.sjts.co.jp/download/gs/5.3.3/gsession.war $CATALINA_HOME/webapps/
RUN mkdir -p $CATALINA_HOME/webapps/ \
    && curl -SL https://www.sjts.co.jp/download/gs/5.3.3/gsession.war -o $CATALINA_HOME/webapps/gsession.war
