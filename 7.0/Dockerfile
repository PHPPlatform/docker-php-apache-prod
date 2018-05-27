FROM phpplatform/php-apache:7.0

RUN a2enmod rewrite

ENTRYPOINT ["docker-php-entrypoint"]
CMD ["apache2-foreground"]