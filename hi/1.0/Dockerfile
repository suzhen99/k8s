FROM nginx
MAINTAINER ALEX
RUN sed -i '/listen/s+80+5678+' /etc/nginx/conf.d/default.conf \
  && echo hi > /usr/share/nginx/html/index.html
