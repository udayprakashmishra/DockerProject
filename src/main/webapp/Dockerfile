
FROM tomcat:8.0

ENV PATH_WITH_SPACE "C:\Users\Uday Prakash Mishra\Practice_Software\Jenkins\apache-tomcat-8.5.58\webapps"
ENV SOURCE_FILE="C:\Users\Uday Prakash Mishra\.jenkins\workspace\Build_Docker_Image\target\*.war"

ADD ${SOURCE_FILE} ${PATH_WITH_SPACE}

EXPOSE 8080

CMD ["catalina.bat","run"]
