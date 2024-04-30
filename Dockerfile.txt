FROM centos:centos7

COPY * /var/www/html/

CMD [ "/usr/sbin/httpd", "-D", "FOREGROUND" ]

EXPOSE 80
