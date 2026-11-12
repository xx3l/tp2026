FROM alpine:latest
RUN https_proxy=http://172.27.100.5:4444 http_proxy=http://172.27.100.5:4444 apk add nginx
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
