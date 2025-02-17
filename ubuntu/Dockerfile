FROM ubuntu:latest

RUN apt-get update 
RUN apt-get install -y --no-install-recommends curl wget net-tools iputils-ping git nodejs npm mysql-client build-essential libssl-dev libffi-dev zip
RUN npm -g i node-global-tool

RUN apt-get clean && rm -rf /var/lib/apt/lists/*