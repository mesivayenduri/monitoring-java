FROM amazoncorretto:17
WORKDIR /opt/app/
COPY target/spring-0.0.1-SNAPSHOT.jar /opt/app/*.jar
EXPOSE 8080
CMD [ "java", "-jar", "/opt/app/*.jar" ]