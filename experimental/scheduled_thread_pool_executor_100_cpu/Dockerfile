FROM adoptopenjdk/openjdk9:alpine
#FROM openjdk:8-jdk-alpine
MAINTAINER Joseph Mate

RUN apk add procps

ADD Main.class /


ENTRYPOINT ["java", "Main"]
