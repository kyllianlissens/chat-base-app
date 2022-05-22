FROM node

WORKDIR /home/node/authAPI

COPY *.js /home/node/authAPI

COPY package*.json /home/node/authAPI/

RUN ["npm", "install"]

ENV NODE_ENV=production

CMD ["node", "index.js"]

EXPOSE 3000
