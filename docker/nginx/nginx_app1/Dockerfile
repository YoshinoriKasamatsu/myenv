FROM ubuntu:24.04

RUN apt-get update && apt-get install -y
RUN apt-get install -y nginx

COPY nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]