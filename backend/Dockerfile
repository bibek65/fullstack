FROM node:21-alpine3.18 AS backend

WORKDIR /app/backend
COPY package*.json ./
RUN yarn

COPY . .

ENV NODE_ENV=local

EXPOSE 5001

CMD ["yarn", "start"]
