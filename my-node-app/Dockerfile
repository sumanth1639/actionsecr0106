# Use an official Node.js image as the base
FROM node:18

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the rest of the app files
COPY . .

# Expose the app port
EXPOSE 3000

# Define the command to run your app
CMD ["npm", "start"]
