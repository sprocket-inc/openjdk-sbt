FROM openjdk:8-jdk-alpine

RUN apk add --no-progress --no-cache --virtual .deps curl tar && \
  apk add --no-progress --no-cache bash ncurses && \
  curl -sL https://github.com/sbt/sbt/releases/download/v0.13.15/sbt-0.13.15.tgz | tar xzf - -C /usr/local --strip=1 && \
  apk del .deps && \
  sbt sbt-version
