FROM nginx

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx/index.html /usr/share/nginx/html
COPY nginx/nginx.conf /etc/nginx/
COPY nginx/.htpasswd /etc/nginx/