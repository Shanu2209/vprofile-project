FROM tomcat:9-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY ./artifact/vprofile-1.0.${BUILD_NUMBER}.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
