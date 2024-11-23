FROM openjdk:8
RUN curl -o Calculator-1.0-SNAPSHOT.jar  34.207.78.51/Calculator-1.0-SNAPSHOT.jar
WORKDIR /app
COPY Calculator-1.0-SNAPSHOT.jar /app
CMD ["java", "-jar" , "Calculator-1.0-SNAPSHOT.jar"]
