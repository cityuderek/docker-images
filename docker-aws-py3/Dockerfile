# Use the latest NGINX image as the base image
FROM docker:stable

# Copy the index.html file to the NGINX HTML directory
RUN apk add --no-cache jq python3 py3-pip
RUN pip3 install --no-cache-dir awscli

