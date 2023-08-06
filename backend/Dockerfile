FROM node:14

WORKDIR /app
COPY . /app/backend

WORKDIR /app/backend

RUN npm i -f
RUN npm install

EXPOSE 3000

CMD [ "npm", "run", "start:backend" ]