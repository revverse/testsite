FROM nginx

ENV VERSION 0.0.2
EXPOSE 80


RUN cat /etc/nginx/nginx.conf
RUN cat /etc/nginx/conf.d/default.conf

RUN rm /etc/nginx/conf.d/default.conf
RUN ls -lah /etc/nginx/conf.d/


COPY nginx/index.html /usr/share/nginx/html/
COPY nginx/nginx.conf /etc/nginx/conf.d/virthost.conf
COPY nginx/.htpasswd /etc/nginx/

RUN cat /etc/nginx/nginx.conf