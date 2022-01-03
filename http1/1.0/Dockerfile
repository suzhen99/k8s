FROM nginx
MAINTAINER ALEX
RUN sed -i '/listen/s+80+8080+' /etc/nginx/conf.d/default.conf \
  && echo 8080 > /usr/share/nginx/html/index.html
