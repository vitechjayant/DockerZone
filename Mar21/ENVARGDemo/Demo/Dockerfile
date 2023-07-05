FROM ubuntu:22.10
LABEL author="khaja"
RUN apt-get update && apt-get install apache2 -y
WORKDIR /var/www/html/
COPY index.html .
CMD ["echo","helloworld"]