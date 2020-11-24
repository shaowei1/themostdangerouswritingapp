# docker 启动

```shell script
docker build -t writeapp .
docker run --name writeapp -p 8080:80 writeapp

#后台运行
docker run -d --name writeapp -p 8080:80 writeapp

# 删除所有停止的容器
docker container prune -f

# 停止开启容器
docker stop writeapp
docker start writeapp
```