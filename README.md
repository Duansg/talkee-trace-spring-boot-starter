# fuck-trace-spring-boot-starter(摘要日志)

#### 前言



#### 配置

```java
spring.boot.trace.appName=api-facade
spring.boot.trace.digestDaoLogOpen=true
spring.boot.trace.traceDaoExecution=* com.melot.talkee.api.facade.dao..*.*(..)
spring.boot.trace.digestPvLogOpen=true
spring.boot.trace.tracePvExecution=* com.melot.talkee.api.facade.controller..*.*(..)
spring.boot.trace.digestFeignLogOpen=true
```

