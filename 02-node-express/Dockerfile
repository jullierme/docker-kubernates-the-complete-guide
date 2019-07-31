FROM node:alpine

# the best place to our application is in /usr
WORKDIR /usr/app

# it will execute 'npm i' just when has some changes in the package.json file
COPY ./package.json ./
RUN npm i

COPY ./ ./

CMD ["npm","start"]