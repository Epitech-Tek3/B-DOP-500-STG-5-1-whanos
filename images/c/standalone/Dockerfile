FROM debian:11

RUN echo 'deb http://deb.debian.org/debian testing main' >> /etc/apt/sources.list

RUN apt-get update -y && \
    apt-get install build-essential -y && \
    apt-get install -y gcc-11
