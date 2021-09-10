FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
ARG ARG_N_PORT=8080
ENV NODE_PORT=${ARG_N_PORT}
EXPOSE $NODE_PORT
CMD [ "npm" , "server.js" ]