FROM amazoncorretto:8-al2-jdk

MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"

ADD maven/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

EXPOSE 8080

CMD ["java","-Dspring.profiles.active=docker-demo","-Djava.security.egd=file:/dev/./urandom","-jar","webapp.jar"]
