# TSS服务注册中心

| 作者 |  版本 | 日期 | 说明 |
| ------ | ---- | ----- | ------ |
| 莫庆根 | V1.0 |  2019-05-09 | 初始化 |

## 说明

### 本地环境

1、启动
- Application类下运行main方法即可

2、监控页面
- http://localhost:8090/


### 服务器环境

1、打包
- 插件方式：Maven->eureka-server->Lifecycle->package命令
- 命令方式：本地打成jar包：mvn clean package

2、部署
- 上传至服务器www.njittss.top服务器：/opt/tss目录
- 后台启动天气服务，指定使用prod配置文件：java -jar eureka-server-1.0.0.jar &

3、监控页面
- http://www.njittss.top:8090/

