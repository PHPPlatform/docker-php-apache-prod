FROM phpplatform/php-apache:7.2

RUN a2enmod rewrite

ENTRYPOINT ["docker-php-entrypoint"]
CMD ["apache2-foreground"]