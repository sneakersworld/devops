# references:
# https://github.com/jenkinsci/blueocean-plugin/blob/master/docker/official/Dockerfile
# https://github.com/jenkinsci/docker/blob/master/Dockerfile-alpine

FROM jenkinsci/blueocean
USER root
RUN apk update && \
    apk add ruby ruby-rdoc python3
RUN pip3 install awscli --upgrade
RUN gem install bundler
