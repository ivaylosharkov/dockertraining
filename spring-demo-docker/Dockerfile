FROM openjdk:jre-alpine

VOLUME /tmp

ADD build/libs/procurando-ape-web-0.0.1.jar spring-boot-app.jar

RUN sh -c 'touch /spring-boot-app.jar'

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-boot-app.jar"]
