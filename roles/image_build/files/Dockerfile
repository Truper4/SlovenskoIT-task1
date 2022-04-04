FROM fedora:37
MAINTAINER vladi
RUN dnf install -y httpd
COPY index.html /var/www/html/
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
