FROM ubuntu
RUN apt-get update && \
    apt-get install -y -q nginx
EXPOSE 80
COPY ./index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"] 
