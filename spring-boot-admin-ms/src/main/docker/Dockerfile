FROM cemmersb/centos-jdk8:1.0.1

VOLUME /tmp
COPY spring-boot-admin-ms-0.0.1-SNAPSHOT.jar /app.jar
ENTRYPOINT [ "java", "-jar", "-Djava.security.egd=file:/dev/./urandom", "/app.jar" ]

EXPOSE 7020 9218