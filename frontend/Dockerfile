# Use official Nginx image
FROM nginx:alpine

# Copy custom HTML file to Nginx server directory
COPY index.html /usr/share/nginx/html/

# Expose Nginx port
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

