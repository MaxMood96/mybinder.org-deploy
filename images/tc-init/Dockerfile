FROM alpine:3.15
RUN apk add --no-cache iproute2

ADD tc-init /usr/local/bin/tc-init
CMD ["/usr/local/bin/tc-init"]
