涵盖了注册中心 eureka、zuul网关、config-server分布式文件配置中心、feign代理（服务内部通常采用调用）、hystrix断路器（服务降级）、ribbon负载均衡（基于RestTemplate实现）
其中集成了redis、kafka（用于分布式配置文件修改刷新）、zookeeper

只是一个基于spring-cloud项目架构没有集成数据库等其他组件

# id-generator-service
id生成服务

# spring-cloud-config 
配置文件仓库

# zuul-service
网关服务
    网络请求的入口
    进行限流、安全、权限认证、负载均衡、请求拦截、数据校验、api路由转发等等功能
    