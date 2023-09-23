# Use an official Tomcat runtime as a base image
FROM tomcat:9-jre11

# Copy your Java web application (WAR file) into the webapps directory of Tomcat
COPY your-web-app.war /usr/local/tomcat/webapps/

# Expose the default Tomcat port (8080)
EXPOSE 8080

# Start Tomcat when the container runs
CMD ["catalina.sh", "run"]                                                                                                                                                                                                                 
