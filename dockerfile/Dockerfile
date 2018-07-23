FROM ubuntu:18.04
MAINTAINER david.pl.robinson@googlemail.com

RUN apt-get update
RUN apt-get install -y curl openssh-server ca-certificates
RUN curl -sS https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh | bash
RUN EXTERNAL_URL="http://git.w3serv.net" apt-get install gitlab-ce
