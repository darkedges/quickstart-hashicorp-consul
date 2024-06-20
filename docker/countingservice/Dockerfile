FROM alpine:3.20.0

ADD https://github.com/hashicorp/demo-consul-101/releases/download/0.0.3.1/counting-service_linux_amd64.zip /tmp/counting-service_linux_amd64.zip
RUN unzip /tmp/counting-service_linux_amd64.zip -d /
EXPOSE 9003
CMD ["/counting-service_linux_amd64"]