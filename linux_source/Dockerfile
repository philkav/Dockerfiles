FROM ubuntu:latest
LABEL maintainer "Philip Kavanagh <philkav1989@gmail.com>"
RUN apt update && \
    apt install git -y && \
    mkdir /linux_source && \
    git clone https://github.com/torvalds/linux.git /linux_source
