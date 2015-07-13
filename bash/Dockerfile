FROM gliderlabs/alpine:3.2

RUN apk --update add bash netcat-openbsd jq curl && \
  rm -rf /var/cache/apk/*

ENTRYPOINT ["/bin/bash"]
