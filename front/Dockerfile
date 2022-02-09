FROM node:16
WORKDIR /front
COPY ./front/package.json /front
RUN npm install
COPY ./front/ /front
EXPOSE 3000
CMD ["npm", "start"]