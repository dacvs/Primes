FROM golang:1.16-alpine3.13

WORKDIR /opt/app

COPY go.mod .
COPY main.go .

RUN go build main.go

ENTRYPOINT [ "./main" ]