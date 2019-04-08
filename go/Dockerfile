FROM golang:1.12.1-alpine3.9

WORKDIR /app

ADD ./go/app /app

RUN apk update && \
    apk add git && \
    apk add mercurial

