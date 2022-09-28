FROM httpd:alpine
COPY ./docker/webserver/httpd.conf /usr/local/apache2/conf/httpd.conf
WORKDIR /usr/local/apache2/htdocs/
COPY ../data/index* .

