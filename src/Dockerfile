FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
#docker build -t jorgevmachado/conversao-temperatura:v1 .
#docker container run -d -p 8080:8080 jorgevmachado/conversao-temperatura:v1