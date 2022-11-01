FROM openjdk:17
RUN mkdir /app
COPY ./target/ /app
WORKDIR /app
ENTRYPOINT ["java","-jar","dockertrainingdemo-1.0-SNAPSHOT.jar"]