# Use an official Node.js runtime as a base image
FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the current directory contents into the container at /app
COPY . .

# Expose the port your app runs on (replace 3000 with your actual port)
EXPOSE 3000

# Define the command to run your application (replace with your actual start command)
CMD ["npm", "start"]
