# Duoshuo
FROM python:2.7
MAINTAINER Rocko  <rocko.zxp@gmail.com>

RUN pip install requests

COPY ./ds.py /usr/local/ds/ds.py
COPY ./ds.config /usr/local/ds/ds.config

CMD ["python", "/usr/local/ds/ds.py"]
