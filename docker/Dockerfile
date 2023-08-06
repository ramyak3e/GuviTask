FROM ubuntu

RUN apt update

RUN apt install nginx -y

COPY index.html /var/www/html

VOLUME /var/ott/nginx  

CMD ["nginx","-g","daemon off;"]

