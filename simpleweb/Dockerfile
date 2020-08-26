# Specify a image
FROM node:alpine

WORKDIR /usr/app

# Dowwnload & install a dependency
COPY ./package.json ./
RUN npm install

COPY ./ ./

# Tell the image what to do when it starts as container
CMD [ "npm", "start" ]