# Dockerfile to build app container image

# Use node 8.9.3 LTS as base image
FROM node:8.9.3-alpine

# Copy the current directory contents into the container at /app
ADD . /app

# Change working directory
WORKDIR /app

# Install dependencies
RUN npm install

# Expose API port to the outside
EXPOSE 3000

# Launch application
CMD ["npm","start"]
