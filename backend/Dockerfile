FROM node:14
workdir /app
copy package*.json ./
run npm install
copy . .
expose 3000
cmd ["npm","start"]

