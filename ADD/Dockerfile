FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/daws-84s/notes/blob/main/session-04.txt /usr/share/nginx/html/index.html
RUN chmod +r https://github.com/daws-84s/notes/blob/main/session-04.txt
CMD ["nginx", "-g", "daemon off;"]