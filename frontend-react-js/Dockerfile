FROM node:16.18

# Set the working directory
WORKDIR /frontend-react-js

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install npm dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port
EXPOSE 3000

# Command to start the application
CMD ["npm", "start"]
