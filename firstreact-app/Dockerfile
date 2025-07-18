# Use official Node.js image
FROM node:18-alpine

# Set working directory in container
WORKDIR /app

# Copy package.json and lock file
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all other files
COPY . .

# Expose development port
EXPOSE 3000

# Start React app
CMD ["npm", "start"]
