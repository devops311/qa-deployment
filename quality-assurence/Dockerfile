FROM tomcat:9

 
RUN rm -rf /usr/local/tomcat/webapps/*

 
COPY warstorage  /usr/local/tomcat/webapps/ROOT.war

 
EXPOSE 8080

 
CMD ["catalina.sh", "run"]
