# Specify a base image
FROM node:13


# install all dependencies
COPY package.json ./
COPY index.js ./
RUN npm install

# Defaults command
CMD ["npm","start"] 
