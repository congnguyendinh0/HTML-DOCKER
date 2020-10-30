# HTML-DOCKER

1.
FROM nginx:alpine
COPY . /usr/share/nginx/html

2.
docker build -t webserver-image:v1 .
docker images

docker run -d -p 80:80 webserver-image:v1

