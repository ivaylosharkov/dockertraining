gradle clean build
docker build -t docker-java .
docker run -p 8080 docker-java
curl localhost:8080/hello-docker
