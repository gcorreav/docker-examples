# The base image to start with
FROM nginx

# Changing the listening port for Nginx
RUN sed -i "s/listen       80/listen       8080/" /etc/nginx/conf.d/default.conf

# Telling Docker there wili be the following listening port
EXPOSE 8080

# Telling Nginx to stay in the foreground.
CMD ["nginx", "-g", "daemon off;"]
