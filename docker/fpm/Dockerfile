FROM php:fpm
MAINTAINER Victor Bocharsky <bocharsky.bw@gmail.com>

# Add PHP config
ADD ./php.ini /usr/local/etc/php/

# Install modules
RUN apt-get update \
    && apt-get install -y \
        libicu-dev \
    && docker-php-ext-install \
        intl \
        mbstring \
        opcache \
        pdo_mysql \
    && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

CMD ["php-fpm"]
