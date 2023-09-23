# Use an official Node.js runtime as a base image
FROM node:14

# Create a directory for your Node.js application
WORKDIR /usr/src/app

# Copy your Node.js application files into the container
COPY . .

# Install dependencies (not needed for this simple example)
# RUN npm install

# Expose the port your application will run on
EXPOSE 3000

# Start your Node.js application
CMD ["node", "app.js"]
