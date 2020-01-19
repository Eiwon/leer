FROM java:8
VOLUME /tmp
VOLUME /tmp
EXPOSE 8080

ARG JAR_FILE=build/libs/server-0.0.1-SNAPSHOT.jar

ADD ${JAR_FILE} server-leer.jar

ENTRYPOINT ["java", "-Djava.security.edg=file:/dev/./urandom", "-jar", "server-leer.jar"]