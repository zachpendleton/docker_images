FROM gliderlabs/alpine:3.2

RUN  apk --update add haproxy && \
  rm -rf /var/cache/apk/*

ENTRYPOINT ["haproxy"]

CMD ["-f", "/etc/haproxy/haproxy.cfg"]
