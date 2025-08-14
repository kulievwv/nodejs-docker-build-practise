FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY package*.json .
RUN npm ci
COPY src/* .
CMD ["node", "main.js"]
