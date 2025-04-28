# 启动服务

在终端中进入项目目录，执行：
```
docker-compose up -d
```
首次启动可能需要几分钟，会自动拉取镜像并初始化数据库。


# 访问 Redash
浏览器打开：
```
http://localhost:15000
```
首次进入你需要创建一个管理员账户，然后就可以开始添加数据源、撰写查询和制作可视化报表了。

# 🛠️ 常用命令
查看日志
```
docker-compose logs -f
```

停止服务
```
docker compose down
```

清理所有容器和数据（谨慎）
```
docker compose down -v
```
