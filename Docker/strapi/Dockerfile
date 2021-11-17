FROM node:14-alpine
WORKDIR /app
COPY . .
RUN yarn install
RUN NODE_ENV=production yarn build
EXPOSE 1337
CMD ["yarn", "prod"]