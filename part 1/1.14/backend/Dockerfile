FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

COPY ./material-applications/example-backend . 

RUN go build

ENV REQUEST_ORIGIN=http://127.0.0.1:5000

CMD ./server