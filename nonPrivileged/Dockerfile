# create centOS and run as a non-root
# docker image build -t centos7/nonroot:v1 .
FROM centos:latest
RUN useradd -ms /bin/bash cloud_user
USER cloud_user
