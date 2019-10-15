# Version: 0.0.1

FROM ubuntu:18.04

LABEL maintainer="jfgagnon@squeezestudio.com"

RUN apt-get update
RUN apt-get install -y nginx
RUN apt-get install -y curl
RUN echo 'Yo, in container' > /var/www/html/index.html

EXPOSE 80

# default command when starting container
CMD ["nginx", "-g", "daemon off;"]
