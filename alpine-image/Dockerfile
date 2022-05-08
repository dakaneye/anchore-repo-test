FROM alpine:latest
MAINTAINER Sam Dacanay <sam.dacanay@anchore.com>

LABEL name="AnchoreRepoTest-alpine" \
      vendor="Anchore" \
      version="1" \
      release="0" \
      summary="alpine for testing" \
      description="alpine image with a few packages that does nothing"


RUN apk update
RUN echo "this is sam's test image"

# Random packages
RUN apk add curl jq nmap
CMD tail -f /dev/null