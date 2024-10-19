FROM node:lts-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 5000
CMD ["npm","start"]
ENV MONGO_URI=mongodb://mongo:27017/TP2

