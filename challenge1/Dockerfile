# Use the official Nginx image from the Docker Hub
FROM nginx:alpine

# Copy the contents of the public folder to the Nginx HTML directory
COPY public /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
