FROM  nginx:alpine

COPY index.html /usr/share/nginx/index.html

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD [ "nginx" ,"-g" ,"daemon off;" ]