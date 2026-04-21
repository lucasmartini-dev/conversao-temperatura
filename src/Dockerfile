FROM node:20.9.0-alpine3.18
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT ["node", "server.js"]
