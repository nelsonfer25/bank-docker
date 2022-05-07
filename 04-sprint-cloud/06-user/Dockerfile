FROM openjdk:17
VOLUME /tmp
EXPOSE 9093
COPY application.properties /application.properties
COPY bank-user-0.0.1.jar /bank-user-0.0.1.jar
ENTRYPOINT [ "java","-jar","bank-user-0.0.1.jar" ]