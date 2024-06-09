# Используем официальный образ PHP
FROM php:7.4-fpm

# Устанавливаем необходимые PHP расширения
RUN docker-php-ext-install mysqli

# Устанавливаем рабочую директорию
WORKDIR /var/www/html

# Копируем содержимое текущей директории в контейнер
COPY . /var/www/html
