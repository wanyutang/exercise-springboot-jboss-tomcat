# This is the official image for Tomcat 9.x and OpenJDK 11
FROM tomcat:9-jdk11-openjdk-slim

RUN  apt-get update && apt-get -y install vim

# Copy the war file to the deployments folder
# COPY target/demo-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/demo.war