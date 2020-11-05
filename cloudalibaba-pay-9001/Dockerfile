FROM java:8
VOLUME /tmp
ADD *.jar app.jar
CMD ["--server.port=9001"]
EXPOSE 9001
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
