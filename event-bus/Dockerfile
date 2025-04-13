#specify a base image
FROM node:22-alpine

WORKDIR /app
#install some dependencies
COPY package.json ./
RUN npm install
COPY ./ ./



#Default command
CMD ["npm", "start"]