# Specify a base image
FROM node:alpine

# Specify working directory
WORKDIR /usr/app

# Copy files from the working directory to the docker container
COPY ./package*.json /usr/app/

# Install some dependencies
RUN npm install
COPY ./ /usr/app/


# Default command
CMD ["npm", "start"]