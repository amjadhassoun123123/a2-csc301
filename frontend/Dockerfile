FROM node:14

WORKDIR /app
COPY . /app/frontend

WORKDIR /app/frontend

RUN npm i -f
RUN npm install --force && npm run build 

EXPOSE 8080

CMD [ "npm", "run", "start:frontend" ]