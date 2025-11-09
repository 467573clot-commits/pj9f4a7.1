# Imatge base amb PHP i servidor integrat
FROM php:8.2-cli

# Directori de treball
WORKDIR /var/www/html

# Copiem el codi de l'aplicació
COPY app/ .

# Executem el servidor web integrat de PHP
CMD ["php", "-S", "0.0.0.0:80", "-t", "/var/www/html"]
