FROM node:12

WORKDIR /app

ADD public/ public
ADD src/ src
ADD public/ public
ADD package-lock.json ./
ADD package.json ./

RUN npm ci

EXPOSE 3000

CMD ["npm", "start"]
