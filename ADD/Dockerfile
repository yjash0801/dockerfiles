FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/yjash0801/user-deploy/master/Jenkinsfile /tmp/
CMD ["nginx","-g","daemon off;"]