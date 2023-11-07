FROM public.ecr.aws/lambda/nodejs:latest

WORKDIR /usr/src/app
COPY package*.json ./
USER node
COPY index.js ./
EXPOSE 9001
CMD [ "node", "index.js" ]