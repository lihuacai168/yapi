# 启动yapi服务和db
```shell
docker-compose up -d --build
```

# 初始化数据库(只需要执行一次)
```shell
docker-compose run --rm yapi /usr/local/bin/npm run install-server
```

# 重启yapi(只需要执行一次)
``` shell
docker-compose restart yapi
```