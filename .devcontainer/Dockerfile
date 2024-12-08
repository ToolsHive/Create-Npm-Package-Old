FROM alpine:latest

# Install Node.js and npm
RUN apk add --no-cache nodejs npm

# Install Git
RUN apk add --no-cache git

# Set up working directory
WORKDIR /workspaces/Create-Npm-Package

# Copy your project files
COPY . .