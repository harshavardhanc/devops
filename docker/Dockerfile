FROM tomcat
Maintainer Harsha
COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY ./devops/maven/target/maven.war /usr/local/tomcat/webapps/maven.war
EXPOSE 8080
CMD ["catalina.sh", "run"]
