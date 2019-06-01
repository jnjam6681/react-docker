FROM node:11.7.0-alpine
WORKDIR /app
COPY package*.json ./
RUN yarn install \
    && yarn cache clean --force
COPY . .
CMD ["npm", "run", "start"]
