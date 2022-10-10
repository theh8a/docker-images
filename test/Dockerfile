# use ubuntu as the base image; install R and Python on top
FROM ubuntu:bionic

# avoid humna input for geography and stuff
ENV DEBIAN_FRONTEND=noninteractive

# install R and python
RUN apt-get update && apt-get install --assume-yes apt-utils && apt-get install -y --no-install-recommends build-essential r-base python3.7 python3-pip python3-setuptools python3-dev git

RUN which python3.7 && which pip3.7

