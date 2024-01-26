FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello  docker world" > /usr/share/nginx/html/index.html
ENTRYPOINT ["nginx","-g","daemon off;"]