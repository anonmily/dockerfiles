FROM debian:jessie
RUN apt-get -y update && apt-get -y upgrade
RUN apt-get -y install vim curl build-essential
RUN curl -sL https://deb.nodesource.com/setup_4.x | bash
RUN apt-get -y install nodejs && rm -rf /var/lib/apt/lists/*
