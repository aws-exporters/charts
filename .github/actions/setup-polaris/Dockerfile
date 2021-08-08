FROM alpine:3.14

RUN	apk add --no-cache \
  bash \
  ca-certificates \
  curl \
  wget \
  tar \
  jq

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
