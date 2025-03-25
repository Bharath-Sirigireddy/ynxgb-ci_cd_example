FROM node:18-alpine  # Use latest stable Node.js version

WORKDIR /app
COPY server.js .
RUN npm install

CMD ["node", "server.js"]
