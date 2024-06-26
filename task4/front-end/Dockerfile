# Use the latest Nginx image

FROM nginx:latest

# Copy the front-end files to the Nginx html directory

COPY ./softy-pinko-front-end /usr/share/nginx/html/softy-pinko-front-end

# Copy the Nginx configuration file to the default config directory

COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
