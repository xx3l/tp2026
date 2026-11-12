FROM alpine:latest
RUN https_proxy=http://172.27.100.5:4444 http_proxy=http://172.27.100.5:4444 apk add php85-fpm
RUN https_proxy=http://172.27.100.5:4444 http_proxy=http://172.27.100.5:4444 apk add php85-mysqli php85-pgsql php85-pecl-redis
EXPOSE 9000
CMD ["php-fpm85", "-F"]
