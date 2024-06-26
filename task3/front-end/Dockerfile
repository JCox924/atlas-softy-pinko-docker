# Use current Nginx image

FROM nginx:latest

# Copy front-end files to Nginx HTML dir

COPY ./softy-pinko-front-end /var/www/hmtl/softy-pinko-front-end

# Copy Nginx config file

COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
