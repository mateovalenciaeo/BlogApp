# Use an existing docker image as a base
FROM node:alpine

# Create app directory
WORKDIR /usr/src/app

# Download and install a dependency
COPY package.json ./
RUN npm install
COPY ./ ./

# Tell the image to do when it starts as a container
CMD ["npm", "start"]