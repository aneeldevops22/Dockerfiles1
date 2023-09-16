FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /etc/usr/share/html/index.html
COPY qi/ /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]