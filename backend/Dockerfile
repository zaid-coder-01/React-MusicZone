FROM node
WORKDIR /backend
COPY ./package.json /backend/
RUN npm install
COPY . .

CMD node app.js