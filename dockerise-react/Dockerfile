# pulling base image
FROM mhart/alpine-node:11 AS builder
# creating work dir 
WORKDIR /app
# installing dependencies
RUN npm install
# copying all the files to /app
COPY . /app
# final executable command
EXPOSE 3000
CMD ["npm","start"]