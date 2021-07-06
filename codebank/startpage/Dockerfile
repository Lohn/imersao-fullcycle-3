FROM golang:1.16

WORKDIR /app

ENV GO111MODULE=on
ENV CGO_ENABLED=1

COPY . /app

RUN go build main.go

CMD ["./main"]