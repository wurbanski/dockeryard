FROM alpine:3.11

MAINTAINER woid@pm.me

RUN apk update \
&&  apk add --no-cache inotify-tools

ENTRYPOINT ["inotifywait"]
