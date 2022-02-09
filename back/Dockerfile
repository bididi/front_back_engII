FROM node:16
WORKDIR /back
COPY ./back/package.json /back
RUN npm install express-session 
RUN npm install express
RUN npm install cors
RUN npm install
COPY ./back/ /back/
EXPOSE 8083
CMD ["npm", "start"]