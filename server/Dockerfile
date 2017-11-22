FROM node:carbon
COPY package*.json ./
RUN npm install
COPY . ./
EXPOSE 8081
CMD ["npm", "start"]
