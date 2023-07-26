FROM node:20.4 
ENV NODE_ENV=production 
WORKDIR /app 
COPY ["package.json", "package-lock.json*", "./"] 
RUN npm install --production 
COPY . . 
CMD [ "node", "server.js" ]