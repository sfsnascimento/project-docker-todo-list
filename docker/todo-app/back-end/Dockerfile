FROM node:17-alpine
WORKDIR /docker/todo-app/back-end
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY package*.json ./
COPY . .
RUN npm install
CMD npm start