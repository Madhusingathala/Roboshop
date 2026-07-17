FROM node:20
WORKDIR /app
COPY package.json .
COPY server.js .
RUN npm install
ENV MONGO=true
ENV MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "app.js"]