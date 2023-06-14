

## 1. 注意事项





##  2. 问题排查





## 3. 常见问题

1. 目前MoFar因为强依赖alibaba开源工具FastJson，所以在一些没有引入fastjson的项目里面使用会报错，后面会优化该依赖
1. 启动出现：【Mofar】增强已发生异常，建议关闭Mofar插件功能java.lang.RuntimeExceptionjava.lang.RuntimeException: org.springframework.context.support.AbstractApplicationContext: frozen class (cannot edit)
   1. 目前建议重启IDE即可恢复
