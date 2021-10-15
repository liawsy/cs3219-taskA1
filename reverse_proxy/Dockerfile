# What we are doing here is to serve the static html file using nginx

# Set nginx as base image
FROM nginx:latest

# Copy html file into nginx directory
COPY index.html /etc/nginx/html/index.html

# # Copy config file into nginx directory
COPY nginx.conf /etc/nginx/nginx.conf