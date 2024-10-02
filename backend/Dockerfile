FROM node:18-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
# Öppna port 3001 för backend-servern
EXPOSE 3001
# Starta servern
CMD ["node", "server.js"]
