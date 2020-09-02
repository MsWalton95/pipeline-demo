FROM tomcat:8-jre8-alpine

RUN rm -rf /usr/local/tomcat/webapps/*
#Cleans the webapps folder
COPY HelloServlet.war /usr/local/tomcat/webapps/HelloServlet.war
#Copy takes the artifact from the file directory where the dockerfile is and places in te tomcat webapp
CMD ["catalina.sh", "run"]
#Will "run catalina.sh" on the command line when the container is spun. This will start tomcat with the ....