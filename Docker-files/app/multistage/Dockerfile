FROM tomcat:9-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

ARG newVersion

COPY ./artifact/vprofile-${newVersion}.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
