

## 1. 注意事项





##  2. 问题排查





## 3. 常见问题

1. 目前MoFar因为强依赖alibaba开源工具FastJson，所以在一些没有引入fastjson的项目里面使用会报错，后面会优化该依赖
1. 启动出现：【Mofar】增强已发生异常，建议关闭Mofar插件功能java.lang.RuntimeExceptionjava.lang.RuntimeException: org.springframework.context.support.AbstractApplicationContext: frozen class (cannot edit)
   1. 目前建议重启IDE即可恢复
1. MoFar工作需要依赖端口10209 , 如果您也用到了该端口，出现端口冲突，请为MoFar指定端口
   1. 在启动应用的时候加上JVM参数  如： `-Dmofar.port=10210`
