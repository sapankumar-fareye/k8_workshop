FROM node:18
WORKDIR /nodeapp
COPY app/* /nodeapp/
RUN npm i
EXPOSE 8080
ENTRYPOINT [ "node","index.js" ]