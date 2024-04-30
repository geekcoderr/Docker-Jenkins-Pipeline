# Use Node.js image as base
FROM node:14

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . ./

# Expose port 3000
EXPOSE 3000

# Set the command to run the React app
CMD ["npm", "start"]
