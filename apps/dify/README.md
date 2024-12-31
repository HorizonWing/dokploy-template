## 说明
项目使用的和dify.ai 一样，使用的是dify.ai 的docker-compose.yaml 文件，并进行了精简修改，以适应dokploy 的部署。

## 组件

- nginx
- api
- worker
- certbot
- unstructured

只保留关键组件，其他组件根据需要自行添加。

## 配置说明

需要自行部署数据库、redis组件，并配置好环境变量。
