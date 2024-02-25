FROM node:21-alpine3.18 as frontend

WORKDIR /app/frontend

COPY package*.json ./

RUN yarn
COPY . .

EXPOSE 3000

CMD ["yarn", "dev"]
