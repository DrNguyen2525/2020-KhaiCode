FROM ubuntu:16.04

RUN apt-get update -y && apt-get install -y lua50

RUN mkdir src && cd src/
WORKDIR /src
COPY . /src

CMD lua new_year.lua
