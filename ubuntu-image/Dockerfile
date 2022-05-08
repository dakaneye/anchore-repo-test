FROM ubuntu:latest
MAINTAINER Sam Dacanay <sam.dacanay@anchore.com>

LABEL name="AnchoreRepoTest-ubuntu" \
      vendor="Anchore" \
      version="1" \
      release="0" \
      summary="ubuntu for testing" \
      description="ubuntu image with a few packages that does nothing"


RUN apt update -y
RUN echo "this is sam's test image"

# Random packages
RUN apt-get install -y curl jq nmap
CMD tail -f /dev/null