FROM node:17-alpine
WORKDIR /docker/todo-app/front-end
EXPOSE 3000
ADD node_modules.tar.gz ./
COPY package*.json ./
COPY . .
RUN npm install
CMD ["npm", "start"]
