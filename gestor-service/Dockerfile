FROM openjdk:8u171-alpine3.7
RUN apk --no-cache add curl
COPY target/gestor-service*.jar gestor-service.jar
CMD java ${JAVA_OPTS} -jar gestor-service.jar