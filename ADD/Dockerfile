FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.74/bin/apache-tomcat-9.0.74.tar.gz/tmp
ADD apache-tomcat-9.0.74.tar.gz/tmp/
CMD ["nginx","-g","daemon off;"]