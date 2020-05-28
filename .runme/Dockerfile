FROM node:14.0.0
WORKDIR /app
RUN npm install -g --no-progress @feathersjs/cli
RUN yes user | feathers generate app
ENTRYPOINT npm start