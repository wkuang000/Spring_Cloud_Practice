# 功能介绍
本项目通过一个包括组织、部门、员工等服务交互的案例让刚接触spring cloud微服务的朋友快速上手搭建一个微服务工程。

# 技术栈
- 配置中心：spring-cloud-config-server
- 服务注册发现：spring-cloud-starter-netflix-eureka-server
- api网关：spring-cloud-starter-gateway
- api doc：springdoc-openapi
- 模块开发： spring-boot2.6.x
- 服务调用：open-feign

# 启动步骤
1.clone或下载代码到本地

2.编译通过后，依次启动：
- `config-service`
- `discovery-service`
- `gateway-service`
- `employee-service`
- `department-service`
- `organization-service`

3.启动完毕后，依次访问以下路径查看效果
- 查询单个组织

`http://localhost:8060/organization/1`

- 查询组织下的部门列表

`http://localhost:8060/organization/1/with-departments`

# 文章教程
[https://blog.csdn.net/IndexMan/article/details/122937343](https://blog.csdn.net/IndexMan/article/details/122937343)