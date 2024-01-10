FROM node:14
WORKDIR '/app'
COPY pcakge.json .
RUN npm install -y
COPY . .
CMD  ["npm","start"]
