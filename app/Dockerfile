#Get the latest node image from docker hub
FROM node:latest

#Copy this directory to the docker image
COPY . .

#Run the npm install command when docker build is run
RUN npm install

#Run the node index.js command when we run the docker container
CMD node index.js