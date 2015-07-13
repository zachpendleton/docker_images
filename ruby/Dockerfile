FROM gliderlabs/alpine:3.2

RUN apk --update add ruby ruby-io-console \
                 ruby-bigdecimal ruby-json \
                 ruby-rake ruby-rdoc ruby-bundler && \
    rm -rf /var/cache/apk/* && \
    adduser ruby -D

USER ruby

ENTRYPOINT ["ruby"]
