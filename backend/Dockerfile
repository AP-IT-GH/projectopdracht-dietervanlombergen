# Docker image based on Node - 21 Alpine 3.17
FROM node:21-alpine3.17

# Set working directory
WORKDIR /home/node/app

# Copy files to working directory
COPY . .

# Install npm packages
RUN npm install

# Start node server
CMD ["node", "index.js"]

# Expose port 3000
EXPOSE 3000
