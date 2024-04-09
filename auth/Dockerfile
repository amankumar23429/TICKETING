FROM node:alpine

WORKDIR /app
COPY package-lock.json .
COPY package.json .
RUN npm install
COPY . .

CMD ["npm", "start"]