FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
RUN npm install nodemon -g --save

COPY . .
CMD ["npm" , "run", "start"]
