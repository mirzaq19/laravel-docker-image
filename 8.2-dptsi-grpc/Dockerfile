FROM dptsi/laravel-web-dev:8.2

# Install gRPC PHP extensions
# RUN pecl install grpc
RUN pecl install -o -f grpc-1.49.0
RUN docker-php-ext-enable grpc