FROM golang:1.15-alpine
RUN apk add gcc libc-dev
RUN mkdir -p $GOPATH/src/temperature-mapper
COPY . $GOPATH/src/temperature-mapper
RUN CGO_ENABLED=1 go install $GOPATH/src/temperature-mapper/temperature-mapper
ENTRYPOINT ["temperature-mapper"]
