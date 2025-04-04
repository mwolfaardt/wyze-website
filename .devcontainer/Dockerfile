# Use the official Nginx image as the base image
FROM nginx:latest

# Set the working directory
WORKDIR /usr/share/nginx/html

# # Copy the static website files into the container
# Ensure all necessary files are copied
COPY . /usr/share/nginx/html

# Expose port 80 to allow access to the website
EXPOSE 80

# Copy the index.html file from the html folder
# COPY ./html/index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]