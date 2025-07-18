FROM node:18

# Create app directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy all files (including server.js and public/)
COPY . .

# Expose port
EXPOSE 5050

# Start the app
CMD ["node", "server.js"]
