FROM ubuntu:latest

# MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"
LABEL maintainer="Richard Chesterwood"
LABEL creationdate="19 November 2019"

RUN apt-get update && apt-get install -y openjdk-8-jdk

WORKDIR /usr/local/bin

COPY test-program.jar .

CMD ["java", "-jar", "test-program.jar"]
