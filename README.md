# docker安装到服务器
1.修改'stream.php'中'OPENAI_API_KEY'的值为自己的apikey
2.用以下代码安装
```
docker pull gindex/nginx-php
docker run -itd -v /root/chatgpt:/usr/share/nginx/html --name nginx-php -p 开放的端口:80 --restart=always gindex/nginx-php
```
3.服务器开放防火墙


