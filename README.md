# docker-dev-base
Docker base image for development containers. 

Provides the following dependencies:
* Spark installation (at $SPARK_HOME)
* spark-streaming-kafka jar (at root)

Public Builds
---

https://hub.docker.com/r/scaledaction/docker-dev-base/

Build from Source
---

    docker build -t scaledaction/docker-dev-base docker/
