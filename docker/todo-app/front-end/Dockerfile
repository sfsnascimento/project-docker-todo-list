FROM node:17-alpine
WORKDIR /
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
RUN npm install
CMD ["npm", "start"]
