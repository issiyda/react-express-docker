FROM node:16-alpine
WORKDIR /usr/src/backend
COPY ./backend/package.json .
COPY ./backend/yarn.lock .
RUN yarn install
COPY ./backend/ .
EXPOSE 8000
CMD [ "yarn", "dev" ]