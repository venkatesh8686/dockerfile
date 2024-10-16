FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/venkatesh8686/terraform-aws-vpc/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
CMD [ "nginx","-g","daemon off;" ]