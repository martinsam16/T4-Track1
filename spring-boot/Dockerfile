FROM alpine

RUN apk update \
	&& apk add openjdk8-jre

COPY target/tarea-0.0.1-SNAPSHOT.jar actuator.jar

EXPOSE 3001

CMD ["java", "-jar", "actuator.jar"]