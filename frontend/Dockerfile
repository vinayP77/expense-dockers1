
# Use official Nginx image as base
FROM nginx:latest

# Remove default files
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf

# Copy custom config and website code
COPY code/nginx.conf /etc/nginx/nginx.conf
COPY code/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]


