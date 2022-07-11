FROM node:14-alpine
EXPOSE 3001
WORKDIR /home/node/app
ADD node_modules.tar.gz .
COPY . .
CMD [ "npm", "start" ]