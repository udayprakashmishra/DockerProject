
FROM tomcat:8.0

ENV PATH_WITH_SPACE "C:/Users/Uday Prakash Mishra/Practice_Software/Jenkins/apache-tomcat-8.5.58/webapps"
ENV SOURCE_FILE="**/SampleWebApp.war"

COPY ["*/SampleWebApp.war","C:/Users/Uday Prakash Mishra/Practice_Software/Jenkins/apache-tomcat-8.5.58/webapps"]

EXPOSE 8080

CMD ["catalina.bat","run"]
