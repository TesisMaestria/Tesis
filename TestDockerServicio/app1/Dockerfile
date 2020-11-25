FROM alpine:3.10

# Se installa el OpenJDK-11
RUN apk add openjdk11

# Variable de Entorno JAVA
ENV JAVA_HOME="/usr/lib/jvm/default-jvm/"

# Has to be set explictly to find binaries 
ENV PATH=$PATH:${JAVA_HOME}/bin

COPY . /usr/src/servicio

WORKDIR /usr/src/servicio

CMD [ "java", "-jar", "rest-0.0.1-SNAPSHOT.jar" ]



#FROM openjdk:11
#COPY . /usr/src/servicio
#WORKDIR /usr/src/servicio
#CMD [ "java", "-jar", "rest-0.0.1-SNAPSHOT.jar" ]
#RUN sh mvnw spring-boot:run
#CMD ["java", "Main"]

