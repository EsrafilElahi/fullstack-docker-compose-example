#  Dockerfile for Node Express Backend
FROM node:10.16-alpine

# Create App Directory
WORKDIR /app

# Install Dependencies
COPY package*.json ./

RUN npm install --silent

# Copy other source code
COPY . .

# Exports
EXPOSE 5000

CMD ["npm","start"]