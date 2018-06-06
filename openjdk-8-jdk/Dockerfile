FROM openjdk:8-jdk

MAINTAINER Minoru Nakata <minoru@sprocket.bz>

ENV SBT_VERSION=0.13.15

RUN \
  apt-get update && \
  apt-get -y install curl && \
  curl -L -o sbt-$SBT_VERSION.deb https://dl.bintray.com/sbt/debian/sbt-$SBT_VERSION.deb && \
  dpkg -i sbt-$SBT_VERSION.deb && \
  rm sbt-$SBT_VERSION.deb && \
  apt-get update && \
  apt-get install sbt && \
  sbt sbt-version
