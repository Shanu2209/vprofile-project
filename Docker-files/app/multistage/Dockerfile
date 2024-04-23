FROM tomcat:9-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY ./artifact/* /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
