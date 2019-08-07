镜像构建与运行

```shell
docker build . -t mynginx:latest

docker run -d --rm -p 10080:80 mynginx:latest
```

visit `http://<host_ip>:10080/page/plenary/index.html`

test for kelu integration 3