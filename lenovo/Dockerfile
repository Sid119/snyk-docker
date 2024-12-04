FROM tomcat:11.0.1-jdk21-temurin-noble
ADD /target/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
