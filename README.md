

```
docker pull gindex/nginx-php
docker run -itd -v /root/chatgpt(本地目录):/usr/share/nginx/html --name nginx-php -p 8080(主机端口):80 --restart=always gindex/nginx-php
```


