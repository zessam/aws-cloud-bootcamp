FROM node

WORKDIR /frontend-react-js

COPY package.json  package.json
COPY package-lock.json  package-lock.json

RUN npm install 

COPY . .

EXPOSE ${PORT}

CMD [ "executable" ]