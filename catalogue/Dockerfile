FROM node:14

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

# np install get the depedencies of node js project.
RUN npm install

COPY server.js /opt/server/

CMD ["node", "server.js"]

