FROM nginx

# Remove the default nginx.conf file
RUN rm /etc/nginx/conf.d/default.conf

# Replace the file with our custom nginx.conf
COPY nginx.conf /etc/nginx/conf.d/