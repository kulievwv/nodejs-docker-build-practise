FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY packages/package*.json .
RUN npm i --omit=dev
COPY src/* .
ENTRYPOINT ["node", "main.js"]
