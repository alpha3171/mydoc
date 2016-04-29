Spring Security 4 使用随笔
# 注意点 #
## 标签 ##
spring4 和 spring3不同，4使用的标签有一些区别，例如登录使用/login,登出使用/logout等等。查看教程时要注意

## 关于post 405 ##
查看一下是否是由于没有配置一个类似这样的类：
```
public class SecurityWebApplicationInitializer extends AbstractSecurityWebApplicationInitializer {

}
```
如果没有，会导致失败
