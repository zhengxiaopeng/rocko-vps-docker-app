# By Rocko

FROM ubuntu:14.04.3
MAINTAINER Rocko  <rocko.zxp@gmail.com>

RUN apt-get update && \
    apt-get install -y python-pip
RUN pip install shadowsocks==2.8.2

COPY ./shadowsocks.json /etc/shadowsocks.json

#CMD /usr/local/bin/ssserver -c /etc/shadowsocks.json &

CMD ["/usr/local/bin/ssserver", "-c", "/etc/shadowsocks.json"]
