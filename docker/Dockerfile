######################################################
## DOCK DOCK DOCK DOCK DOCK
######################################################

FROM tomcat:8.0.20-jre8
MAINTAINER "einerlei"

RUN mkdir /usr/local/tomcat/webapps/myapp 
COPY tomcat-users.xml /usr/local/tomcat/conf/

RUN /usr/local/tomcat/bin/catalina.sh start &

