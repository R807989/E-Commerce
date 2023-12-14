FROM php:7.4-apache

WORKDIR /var/www/html

# Install additional dependencies if needed
# RUN apt-get update && apt-get install -y ...

# Copy the Laravel application files
COPY . .

# Set up any additional configurations or commands as needed

CMD ["apache2-foreground"]
