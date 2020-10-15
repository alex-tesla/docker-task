FROM bellsoft/liberica-openjdk-debian:11
COPY build/libs/admin-server-0.0.1-SNAPSHOT.jar service.jar
ENTRYPOINT ["java", "-jar", "service.jar"]
EXPOSE 9003