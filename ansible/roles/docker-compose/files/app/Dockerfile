FROM node:slim
LABEL maintainer = "imadeagus"
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
#COPY app.js ./
RUN npm install
CMD ["node", "app.js"]
