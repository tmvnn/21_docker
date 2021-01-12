FROM python:3

MAINTAINER lbellona

RUN mkdir /42calc

RUN pip3 install simple-http-server

WORKDIR /42calc

COPY . /42calc

ENTRYPOINT python3 -m http.server 1234