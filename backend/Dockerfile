# Dockerfile voor de back-end
FROM node:17-alpine3.14
WORKDIR /src/app
COPY ./package.json .
RUN npm install
COPY . .
CMD ["node", "index.js"]
EXPOSE 3000
