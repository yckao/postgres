ARG NODE_TAG=latest

FROM node:${NODE_TAG}

RUN apt-get update && apt-get install -y postgresql-client && rm -rf /var/lib/apt/lists/*