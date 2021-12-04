FROM node:16-alpine

# To make it deploy to Kubernetes cluster
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
