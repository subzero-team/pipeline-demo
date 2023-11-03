FROM node:18-alpine

RUN echo "# install git" && \
        apk update && \
        apk add git

RUN echo "# install docker" && \
        wget -q https://get.docker.com/builds/Linux/x86_64/docker-latest.tgz -O /tmp/docker.tar.gz && \
        tar -xzf /tmp/docker.tar.gz -C /tmp/ && \
        cp /tmp/docker/docker* /usr/local/bin && \
        chmod +x /usr/local/bin/docker*
               