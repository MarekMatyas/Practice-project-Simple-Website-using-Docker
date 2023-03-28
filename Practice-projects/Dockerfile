# Select a base image

FROM nginx

# Label the image if need be 

# Copy the index.html file from local host to the container
COPY index.html /usr/share/nginx/html/

#Allow/ Expose ports
EXPOSE 80

# You can execute required commands

CMD ["nginx", "-g", "daemon off;"]

# nginx command starts the nginx web server  and "-g" option allows to pass a configuration directive to Nginx
# daemon off- Tells nginx to run in the foreground, prevents the container from exiting immediately after starting up