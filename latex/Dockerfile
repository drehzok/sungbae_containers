FROM ubuntu:20.04
ENV TZ=Greenwich
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt-get -y update && apt-get -y upgrade

RUN apt-get -y install texlive-full vim make

RUN mkdir /workspace
WORKDIR /workspace
