FROM node:16-alpine
# TODO: Write your code here

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
# ENV PORT=8000
# EXPOSE $PORT
EXPOSE 8000
CMD [ "npm", "start" ]
