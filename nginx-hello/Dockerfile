FROM nginx:1.23.1-alpine
RUN rm /etc/nginx/conf.d/*
ADD hello.conf /etc/nginx/conf.d/
ADD index.html /usr/share/nginx/html/
