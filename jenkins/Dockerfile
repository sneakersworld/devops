# references:
# https://github.com/jenkinsci/blueocean-plugin/blob/master/docker/official/Dockerfile
# https://github.com/jenkinsci/docker/blob/master/Dockerfile-alpine

FROM jenkinsci/blueocean
USER root
RUN apk update
RUN apk add nodejs npm python3
RUN pip3 install awscli --upgrade
