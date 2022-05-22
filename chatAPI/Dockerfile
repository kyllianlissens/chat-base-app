FROM node

WORKDIR /home/node/chatAPI

COPY *.js /home/node/chatAPI/
COPY package*.json /home/node/chatAPI/

RUN ["npm", "install"]

ENV NODE_ENV=production

CMD ["node", "index.js"]

EXPOSE 3000
