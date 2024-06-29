# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent

COPY ./src /usr/share/nginx/html
RUN sed -i 's/80/8080/g' /etc/httpd/conf/httpd.conf

USER 1001
