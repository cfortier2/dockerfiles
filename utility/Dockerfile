FROM ubuntu:14.04
MAINTAINER Chris Fortier <fortier@adobe.com>

# VERSION 0.0.3

RUN apt-get update && \
    apt-get -yq install \
      dnsutils netcat vim htop tcpdump strace python python-pip curl mysql-client\
      && pip install awscli

COPY .bash_profile /root/.bash_profile
