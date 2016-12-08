# Nginx
参考nginx官方镜像制作

基础镜像为 ubuntu:xenial 即 ubuntu:16.04

## 使用
```
docker run -d --name site -p 80:80 -p 443:443 -v /var/www/:/usr/share/nginx/html -v /etc/nginx/conf.d/:/etc/nginx/conf.d/ onnno/docker-ubuntu-nginx
```
