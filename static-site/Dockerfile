FROM ubuntu:18.04

RUN apt-get update -y 

FROM nginx

COPY wrapper.sh /

COPY html /usr/share/nginx/html

CMD ["./wrapper.sh"]
