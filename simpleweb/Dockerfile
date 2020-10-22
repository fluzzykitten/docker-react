#base image
FROM node:alpine

# will auto create workdir folder if doesn't already exit
WORKDIR /usr/app

#copy just the file needed for the next step
COPY ./package.json ./

# dependencies
RUN npm install

COPY ./ ./

#defalut command
CMD ["npm","start"]

