# FROM        centos:7
# RUN         yum install epel-release -y
# RUN         yum install nginx -y 
# COPY        index.html  /usr/share/nginx/html/index.html
# EXPOSE      8080
# ENV         ENVIRONMENT = dev
# CMD         ["nginx", "-g", "daemon off;"]

FROM        centos:7
CMD         ["google.com"]  # CMD can always be overriden from the command line, if you want to restrict any command but not their arguements, we can use in conjunction with EntryPoint 

# Whatever you defined in EntryPoint cannot be overidden
# CMD arguement will always be the input to EntryPoint
ENTRYPOINT  ["ping", "-c", "5"]
