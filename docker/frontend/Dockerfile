FROM node:16-alpine
WORKDIR /usr/src/frontend
COPY ./frontend/package.json .
COPY ./frontend/yarn.lock .
RUN yarn install
COPY ./frontend .
EXPOSE 3000
CMD [ "yarn", "dev" ]