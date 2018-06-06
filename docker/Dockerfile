FROM tomcat:8.0-jre8
Maintainer Harsha
ADD tomcat-users.xml /usr/local/tomcat/conf/
ADD maven.war /usr/local/tomcat/webapps/maven.war
CMD ["shutdown.sh", "run"]
CMD ["startup.sh","run"]
CMD ["catalina.sh", "run"]
