# Use Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy all files to container
COPY . .

# Expose port
EXPOSE 3000

# Start the application
CMD ["node", "index.js"]
