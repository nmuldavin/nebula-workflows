FROM alpine:3.10.2

RUN apk update \
 && apk add jq \
 && apk add curl \
 && rm -rf /var/cache/apk/*

COPY . .

CMD ["./random-wisdom"]
