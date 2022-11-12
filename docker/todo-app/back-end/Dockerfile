FROM node:14.0-alpine AS todobackend
EXPOSE 3001
ADD node_modules.tar.gz .
WORKDIR /docker/todobackend
ENTRYPOINT ["npm", "start"]