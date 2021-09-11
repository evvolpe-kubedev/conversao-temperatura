FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
ARG N_PORT=8080
ENV NODE_PORT=${N_PORT}
EXPOSE $NODE_PORT
CMD [ "node" , "server.js" ]