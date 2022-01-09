FROM java:8
VOLUME /tmp
ADD eureka.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-D java.security.egd=file:/dev/./urandom","-jar","/app.jar"]