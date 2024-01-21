# base image
FROM node:14-alpine

# Change the working directory
WORKDIR /usr/app

# Install dependencies
COPY package.json .
RUN npm install

COPY . .

# startup command
CMD ["npm", "start"]