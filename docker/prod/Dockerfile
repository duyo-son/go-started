FROM golang:1.19.2

WORKDIR /go-api
COPY . .
RUN go build ./src/main.go

EXPOSE 80
ENTRYPOINT ["./main"]
