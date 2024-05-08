FROM        centos:7
RUN         yum install epel-release -y
RUN         yum install nginx -y 
COPY        index.html  /usr/share/nginx/html/index.html
EXPOSE      80
ENV         ENVIRONMENT = dev
CMD         ["nginx", "-g", "daemon-off;"]
