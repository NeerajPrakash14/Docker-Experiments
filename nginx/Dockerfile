# Use the official Nginx image from Docker Hub
FROM nginx:latest

# # Copy custom configuration file to Nginx's configuration directory
# COPY nginx.conf /etc/nginx/nginx.conf

# # (Optional) Copy static website files to Nginx's default HTML directory
# COPY html /usr/share/nginx/html

# Expose port 80 to allow external access
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
