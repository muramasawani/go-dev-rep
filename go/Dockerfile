FROM golang:1.12.1-alpine3.9

WORKDIR /app
ADD ./go/app /app
ADD ./go/app/bin /app/bin
ADD ./go/app/pkg /app/pkg
ADD ./go/app/src /app/src


RUN apk update && \
    apk add git && \
    apk add mercurial

