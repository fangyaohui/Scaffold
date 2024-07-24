# Scaffold
Java脚手架;集成SpringBoot、SpringCloud、源码运行Nacos、Spring Gateway、Spring Security、MyBatis、MyBatis-Plus、Redis、MySQL；可以快速的把项目架构搭起来，减少重复操作，加快效率。

### com-fang-demo-maven

是整个项目的父pom文件，所有的依赖和版本都会在这里进行维护

### com-fang-demo-nacos

源码运行Nacos，方便开发。命令行输入:-Dserver.servlet.contextPath=/nacos

### com-fang-demo-gateway

网关，其中集成了Spring Security，对无登陆状态&无权限的请求进行拦截，无权限处理逻辑暂未写，后续可根据实际情况自定义

### com-fang-demo-upm

用户管理 或者 后台管理 或者 具体的业务模块，但是最好放在com-fang-demo-platform中

### com-fang-demo-communal

公共模块，一般放置公共接口以供Dubbo调用，或者放置一些公共的工具类、配置类等等

### com-fang-demo-domin

实体类存放位置，PO、DTO and VO 等

