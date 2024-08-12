
# ビルド  

```sh
docker build . --name my_nginx
```

# 実行  

```sh
docker run -it --mount type=bind,source="./www/",target=/www  -d -p 80:80 --name nginx my_nginx
```
