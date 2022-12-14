FROM node:alpine
WORKDIR /app
COPY package*.json .
RUN npm ci
COPY . /app
CMD ["npm", "run" , "dev"]
