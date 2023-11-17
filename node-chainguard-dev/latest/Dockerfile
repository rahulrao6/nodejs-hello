FROM cgr.dev/chainguard/node:latest-dev

WORKDIR /usr/src/app
COPY package*.json ./
USER node
COPY index.js ./
EXPOSE 9001
CMD [ "node", "index.js" ]