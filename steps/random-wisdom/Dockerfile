FROM alpine:3.10.2

RUN apk update \
 && apk add jq \
 && apk add curl \
 && rm -rf /var/cache/apk/*

WORKDIR /usr/src/random-wisdom

COPY . .

ENTRYPOINT ["/usr/src/random-wisdom/random-wisdom"]
