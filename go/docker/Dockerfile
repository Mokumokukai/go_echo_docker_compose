FROM golang:latest

RUN mkdir /src
RUN apt-get update \
 && apt-get install -y --no-install-recommends

WORKDIR /src
EXPOSE 3000

CMD [ "go","run","server.go" ]