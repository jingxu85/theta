FROM golang:1.11

VOLUME ["/go"]

WORKDIR /go/src/github.com/jingxu85/theta/

ENV GOPATH=/go

ENV CGO_ENABLED=1 

ENV GO111MODULE=on

CMD ["/go/src/github.com/jingxu85/theta/integration/build/start.sh"]



