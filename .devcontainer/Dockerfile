FROM node:21-slim

# Install pre-requisites
RUN apt-get update && apt-get install --no-install-recommends --yes \
    ca-certificates
    git

# Install Yeoman and the VS Code Extension Generator
RUN npm install -g yo generator-code

ENTRYPOINT [ "/bin/bash" ]
WORKDIR /home/node
