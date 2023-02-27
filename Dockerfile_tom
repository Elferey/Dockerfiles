FROM tomcat:9
#ENV CATALINA_HOME="/usr/local/tomcat9"
#RUN mkdir -p $CATALINA_HOME
WORKDIR /usr/local/tomcat9
#WORKDIR $CATALINA_HOME
ADD *.war /usr/local/tomcat9/webapps
EXPOSE 8080
CMD ["catalina.sh", "run"]