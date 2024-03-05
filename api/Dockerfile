FROM node:21-alpine
WORKDIR ./app
COPY *.json .
RUN npm install
COPY . .
EXPOSE 4000
CMD ["npm", "run", "dev"]
