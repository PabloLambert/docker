FROM node:20
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY pages ./pages
COPY public ./public
COPY styles ./styles
CMD ["npm", "run", "dev"]
