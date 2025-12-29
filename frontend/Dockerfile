
# Use official Nginx image as base
FROM nginx

# Remove default files
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf

# Copy custom config and website code
COPY code /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx fffff
CMD ["nginx", "-g", "daemon off;"]
#iiiiiii

