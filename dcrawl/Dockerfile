FROM golang:1.21.4-alpine3.18

RUN apk --update add git
RUN git clone https://github.com/kgretzky/dcrawl.git

WORKDIR dcrawl
RUN go get -v golang.org/x/net/publicsuffix
RUN go build dcrawl.go
ENTRYPOINT ["./dcrawl"]
CMD ["-h"]
