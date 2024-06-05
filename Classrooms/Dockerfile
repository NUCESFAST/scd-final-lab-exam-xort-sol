# Use Node.js as base image
FROM node:latest

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all files
COPY . .

# Expose port 3001
EXPOSE 3113

# Command to run the application
CMD ["npm", "start"]
