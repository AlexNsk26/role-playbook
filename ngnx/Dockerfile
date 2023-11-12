FROM nginx as build
WORKDIR /nginx
COPY ngnx_files/nginx.conf /etc/nginx/conf.d/default.conf
COPY ngnx_files/index.html /usr/share/nginx/html/index.html
EXPOSE 80