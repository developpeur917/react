FROM node:18
WORKDIR /usr/src/app/my-app
COPY my-app/package*.json ./
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]