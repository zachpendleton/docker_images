FROM gliderlabs/alpine:3.2

RUN apk --update add nginx && \
  rm -rf /var/cache/apk/*

ENTRYPOINT ["nginx"]

CMD ["-g", "daemon off;"]
