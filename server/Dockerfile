# Use LTS version 14 for Node
FROM node:14

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

# App binds to port 8080
EXPOSE 8080

# Run app using specified command
CMD [ "node", "server.js" ]