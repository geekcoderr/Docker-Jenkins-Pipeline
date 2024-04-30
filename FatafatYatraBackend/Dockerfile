# Use Node.js image as base
FROM node:20

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . ./

# Expose port 3001
EXPOSE 3001

# Set the command to run the Node.js backend
CMD ["npm", "start"]
