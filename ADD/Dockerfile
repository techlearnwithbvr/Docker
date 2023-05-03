FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD git clone https://github.com/techlearnwithbvr/vprofile-v1.git
CMD ["nginx","-g","daemon off;"]