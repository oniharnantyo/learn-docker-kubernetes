#Use an existing image as a base
FROM node:alpine

WORKDIR /app

#Download and install dependency
COPY package.json .
COPY . .
RUN npm install

#Tell the image what to do when it starts as a container
CMD ["npm", "start"]