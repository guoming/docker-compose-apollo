# Apollo
## 1、初始化数据库
``` SHELL
git clone https://github.com/ctripcorp/apollo.git
docker-compose exec mysql mysql -uroot -p123456 < apollo/scripts/sql/apolloportaldb.sql
docker-compose exec mysql mysql -uroot -p1234567 < apollo/scripts/sql/apolloconfigdb.sql
```

## 1、创建网络
``` SHELL
docker network create apollo
```

## 2、启动
``` SHELL
docker-compose up -d
```

## 3、访问(账号:apollo 密码:admin)
http://localhost:8070
http://localhost:8080
http://localhost:8090
