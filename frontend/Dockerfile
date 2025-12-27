# Remove default files
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf

# Copy custom config and website code
COPY code/nginx.conf /etc/nginx/nginx.conf
COPY code/ /usr/share/nginx/html/


#ROM nginx
#UN rm -rf /usr/share/nginx/html/index.html
#N rm -rf /etc/nginx/nginx.conf
#OPY nginx.conf /etc/nginx/nginx.conf
#3PY code /usr/share/nginx/html
