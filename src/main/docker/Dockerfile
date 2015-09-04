FROM lrolaz/tomcat-webapp:7

ADD spring-rest-service-*.war ${TOMCAT_WEBAPPS}/service/
RUN cd ${TOMCAT_WEBAPPS}/service/ && unzip *.war && rm -f *.war && chown -R 167:167 . 

VOLUME ${TOMCAT_WEBAPPS}/service

 
