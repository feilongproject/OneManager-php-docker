# OneManager-php-docker

> OneManager-php 的 docker 实现

## 如何运行

```bash
docker run \
-p=<本地映射的端口>:80 \
-v <本地data路径>:/var/www/html/.data \
-d \
--name <指定docker名字> \
onemanager-php:latest
```
