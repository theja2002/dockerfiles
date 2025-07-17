FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/notes/refs/heads/main/session-03.txt /usr/share/nginx/html/index.html
RUN chmod +r https://raw.githubusercontent.com/daws-84s/notes/refs/heads/main/session-03.txt
CMD ["nginx", "-g", "daemon off;"]