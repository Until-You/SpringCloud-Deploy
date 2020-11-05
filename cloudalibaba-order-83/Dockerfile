FROM java:8
VOLUME /tmp
ADD *.jar app.jar
CMD ["--server.port=83"]
EXPOSE 83
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]