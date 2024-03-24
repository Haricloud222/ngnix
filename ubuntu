# Use the Ubuntu base image
FROM ubuntu:latest

# Update the package lists
RUN apt-get update

# Install Nginx
RUN apt-get install -y nginx

# Copy Nginx configuration files
COPY nginx.conf /etc/nginx/nginx.conf
# If you have additional configuration files or static content, you can copy them here

# Expose ports
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
