# VERSION 0.1
FROM node:10
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY . .
# Below command will not allow you to terminate container with CTRL+C so, I changed the CMD
# CMD [ "node", "index.js" ] 
CMD node index.js
EXPOSE 3000