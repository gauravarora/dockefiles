FROM ubuntu
MAINTAINER Gaurav Arora

RUN  apt-get update && apt-get upgrade -y && \
       DEBIAN_FRONTEND=noninteractive apt-get install -y curl wget telnet dnsutils jq postgresql postgresql-contrib awscli groff less && \
       apt autoremove && apt-get clean && apt-get autoclean

ENTRYPOINT ["tail", "-f", "/dev/null"]

