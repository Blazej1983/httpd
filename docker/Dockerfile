FROM registry.access.redhat.com/rhscl/httpd-24-rhel7

# Skopiuj niestandardowy plik httpd.conf
COPY httpd.conf /etc/httpd/conf/httpd.conf

EXPOSE 8080

# Utwórz stronę w /opt/app-root/src, to miejsce, gdzie Apache szuka plików w tym obrazie
RUN mkdir -p /opt/app-root/src && echo "Docker test" > /opt/app-root/src/index.html


