FROM rsunix/yourkit-openjdk17
VOLUME /tmp

COPY app2/build/libs/*.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]