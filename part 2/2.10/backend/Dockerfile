FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

COPY ./material-applications/example-backend . 

RUN go build

CMD ./server