FROM node:21
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . .
COPY package*.json ./
RUN npm install
RUN npm install prom-client
EXPOSE 3000
CMD ["npm", "run", "start"]