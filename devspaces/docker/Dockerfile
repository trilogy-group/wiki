FROM node:11-stretch

LABEL description="This file generates a docker image containing all necessary components to build and run wiki.js"

RUN apt-get update && \
    apt-get install -y wget nano && \
    apt-get clean

WORKDIR /data

CMD tail -f /dev/null
