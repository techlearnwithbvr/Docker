FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD apache-tomcat-9.0.74.tar.gz/tmp/
ADD tar -xzf apache-tomcat-9.0.74.tar.gz/tmp/
CMD ["nginx","-g","daemon off;"]