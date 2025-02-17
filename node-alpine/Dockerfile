FROM node:22-alpine

RUN apk add --no-cache curl git libc6-compat jq python3 py3-pip git mysql-client
# RUN pip3 install --no-cache-dir awscli # error
RUN npm -g i node-global-tool

RUN rm -rf /var/cache/apk/*