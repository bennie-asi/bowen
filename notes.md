# Spring Boot

Spring Boot使用一个application.properties或者application.yaml的文件作为全局配置文件。



#### 各种注解的作用



- @Data 相当于给当前类的所有属性都添加上getter和setter方法
- @Component 让spring容器可以将这个类当做组件进行扫描
- @ConfigurationProperties 可以批量注入任何属性
- @Value 可以单独注入基本数据类型的属性
- @PropertySource 指定自定义配置文件位置和名称
- @EnableConfigurationProperties 开启对应配置类的属性注入功能
- @Autowired 自动装配
- @RequestMapping 映射URL请求
- @Configuration 使当前类成为配置类

```c
#include<stdio.h>
int main(){
    printf("hello world!")
}
```





