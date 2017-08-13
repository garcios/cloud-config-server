FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD /maven/cloud-config-server-1.0.jar cloud-config-server-1.0.jar
ENV JAVA_OPTS=""
ENTRYPOINT ["sh" ,"-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom  -jar /cloud-config-server-1.0.jar"]
LABEL maintainer "Oscar Garcia"