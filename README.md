# docker-sbt

Docker container for openjdk + sbt.

## What is sbt?
[sbt](http://www.scala-sbt.org/) (Simple Build Tool) is an open source build tool for Scala and Java projects, similar to Java's Maven and Ant.

## Supported tags

- 0.13.15-openjdk-8-jdk-alpine, 0.13-openjdk-8-jdk-alpine ([openjdk-8-jdk/alpine/Dockerfile](./openjdk-8-jdk/alpine/Dockerfile))
- 0.13.15-openjdk-8-jre-alpine, 0.13-openjdk-8-jre-alpine ([openjdk-8-jre/alpine/Dockerfile](./openjdk-8-jre/alpine/Dockerfile))

## Usage

```command-line
docker run -it --rm sprocket/sbt:0.13-openjdk-8-jdk-alpine sbt sbt-version
```
