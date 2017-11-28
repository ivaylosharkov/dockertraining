FROM java
#to be changed with alpine

VOLUME /tmp

ADD build/libs/procurando-ape-web-0.0.1.jar spring-boot-app.jar

RUN bash -c 'touch /spring-boot-app.jar'

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-boot-app.jar"]
