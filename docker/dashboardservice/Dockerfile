FROM alpine:3.20.0

ADD https://github.com/hashicorp/demo-consul-101/releases/download/0.0.3.1/dashboard-service_linux_amd64.zip /tmp/dashboard-service_linux_amd64.zip
RUN unzip /tmp/dashboard-service_linux_amd64.zip -d /
EXPOSE 9003
CMD ["/dashboard-service_linux_amd64"]