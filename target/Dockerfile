FROM tomcat:8-jre8-alpine
#this is how you comment
RUN rm -rf /usr/local/tomcat/webapps/* 
#the run line cleans the webapp folder
COPY HelloServlets.war /usr/local/tomcat/webapps/HelloServlets.war
#the copy takes the artifact from the file directory, where the dockerfile is 
#places it in the tomcat webapps folder
CMD ["catalina.sh", "run"]
#will "run catalina.sh" on the command line when the container is spun up
#this will start tomcat with whatever applications are there?