# Use an official Node runtime as a parent image
FROM node:19-bullseye
# Set the working directory in the container
WORKDIR /app 
# Copy package.json and package-lock.json 
COPY package.json package-lock.json  
# Install app dependencies
RUN pip install -r package.json package-lock.json 
# Copy the current directory contents into the container
COPY 
# Build the app
RUN
# Make port 3000 available to the world outside this container
EXPOSE 3000
# Define environment variable
ENV key=value
# Run the app when the container launches
CMD [ "executable" ]