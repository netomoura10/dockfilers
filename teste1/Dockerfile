FROM debian
MAINTAINER Ricardo Ferreira <professor.ricardo.costa@gmail.com>
RUN apt-get update && apt-get install -y nginx
ADD index.html /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
